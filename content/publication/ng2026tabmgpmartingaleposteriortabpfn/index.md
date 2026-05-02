---
title: 'TabMGP: Martingale posterior with TabPFN'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kenyon Ng
  - Edwin Fong
  - David T. Frazier
  - jeremias
  - Susan Wei
date: '2026-02-15T00:00:00Z'
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


abstract: "Bayesian inference provides principled uncertainty quantification but is often limited by challenges of prior and likelihood elicitation. The martingale posterior (MGP) (Fong et al., 2023) offers an alternative by replacing these requirements with a predictive rule. Additionally MGP focuses inference on parameters defined through a loss function. This framework is especially resonant in the era of foundation transformers; practitioners increasingly leverage models like TabPFN for their state-of-the-art capabilities, yet often require epistemic uncertainty for a scientific estimand  that need not parameterise the model's implicit latent model. The MGP provides the mechanism to recover these posterior distributions. We introduce TabMGP, an MGP built on TabPFN for tabular data. TabMGP produces credible sets with near-nominal coverage and often outperforms both handcrafted MGP constructions and standard Bayesian baselines."


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
    url: https://arxiv.org/abs/2510.25154

url_pdf: ''
url_code: ''
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
