---
title: 'Amortised and provably-robust simulation-based inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ayush
  - harita
  - yuga
  - fx
date: '2026-02-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: 'Complex simulator-based models are now routinely used to perform inference across the sciences and engineering, but existing inference methods are often unable to account for outliers and other extreme values in data which occur due to faulty measurement instruments or human error. In this paper, we introduce a novel approach to simulation-based inference grounded in generalised Bayesian inference and a neural approximation of a weighted score-matching loss. This leads to a method that is both amortised and provably robust to outliers, a combination not achieved by existing approaches. Furthermore, through a carefully chosen conditional density model, we demonstrate that inference can be further simplified and performed without the need for Markov chain Monte Carlo sampling, thereby offering significant computational advantages, with complexity that is only a small fraction of that of current state-of-the-art approaches.'


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
    url: https://arxiv.org/abs/2602.11325

url_pdf: ''
url_code: https://github.com/bharti-ayush/nsm-bayes
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
