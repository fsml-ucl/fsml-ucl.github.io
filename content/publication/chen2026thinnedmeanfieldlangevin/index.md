---
title: 'Thinned Mean Field Langevin Dynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - hudson
  - Heishiro Kanagawa
  - fx
  - Chris J. Oates
  - Lester Mackey
date: '2026-02-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML 2026*


abstract: "Several important learning tasks can be formulated as minimizing an entropy-regularized objective over an appropriate space of probability distributions. Mean-field Langevin dynamics (MFLD) facilitate computation in this general context, casting the minimizer as the invariant distribution of a McKean--Vlasov process, which can be numerically discretized using $N$ particles and thus simulated. However, simulating this interacting particle system has computational complexity of order $N^2$. Motivated by recent research into kernel thinning, we propose KT-MFLD, in which each particle interacts only with a thinned particle coreset of size $O(N^{1/2})$. KT-MFLD thus reduces the computational complexity to order $N^{3/2}$ while, under mild regularity conditions, achieving the same convergence guarantees (up to logarithmic factors) as MFLD. Our theoretical analysis is empirically confirmed on tasks including the training of student-teacher neural networks, quantization with maximum mean discrepancy, and computation of predictively-oriented posteriors in a post-Bayesian framework."


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
    url: https://arxiv.org/abs/2605.28589

url_pdf: ''
url_code: https://github.com/hudsonchen/thinned_mfld
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
