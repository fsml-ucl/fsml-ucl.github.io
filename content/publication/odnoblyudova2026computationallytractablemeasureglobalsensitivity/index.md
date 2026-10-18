---
title: 'A computationally-tractable measure of global sensitivity for sampling-based Bayesian inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - arina
  - harita
  - fx

date: '2026-05-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: 'Bayesian inference can often be sensitive to the choice of hyperparameters of the prior or likelihood, yet defining and quantifying this sensitivity in a principled and computationally feasible way remains challenging in practice. Unfortunately, existing sensitivity methods are rarely applicable in modern Bayesian workflows due to their high computational cost and poor performance in moderate to high dimensions. To address these limitations, we introduce a new approach to global sensitivity analysis based on the Fisher divergence. Our method only requires a set of samples from a reference posterior and the ability to evaluate score functions, making it broadly computationally tractable. Under mild regularity conditions, it controls changes in the whole posterior, and provides a bound on the impact of perturbations on the first two moments. We demonstrate these strengths on challenging Bayesian inference problems which are practically out of reach of existing approaches, including generalised Bayesian inference for unnormalised models, inference in Bayesian models of time series, and neural simulation-based inference.'


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
    url: https://arxiv.org/abs/2605.28099

url_pdf: ''
url_code: 'https://github.com/jularina/fd-sens'
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
