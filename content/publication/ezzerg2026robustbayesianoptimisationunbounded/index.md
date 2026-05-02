---
title: 'Robust Bayesian Optimisation with Unbounded Corruptions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - abdelhamid
  - Ilija Bogunovic
  - jeremias
date: '2026-02-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML 2026*


abstract: "Bayesian Optimization is critically vulnerable to extreme outliers. Existing provably robust methods typically assume a bounded cumulative corruption budget, which makes them defenseless against even a single corruption of sufficient magnitude. To address this, we introduce a new adversary whose budget is only bounded in the frequency of corruptions, not in their magnitude. We then derive RCGP-UCB, an algorithm coupling the famous upper confidence bound (UCB) approach with a Robust Conjugate Gaussian Process (RCGP). We present stable and adaptive versions of RCGP-UCB, and prove that they achieve sublinear regret in the presence of up to  $O(T^{1/4})$ and $O(T^{1/7})$ corruptions with possibly infinite magnitude. This robustness comes at near zero cost: without outliers, RCGP-UCB\'s regret bounds match those of the standard GP-UCB algorithm."


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
  - icon:
    icon_pack: fas
    name: 'arXiv'
    url: https://arxiv.org/abs/2511.15315

url_pdf: ''
url_code: https://github.com/EZZERG/RCGP
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false
---
