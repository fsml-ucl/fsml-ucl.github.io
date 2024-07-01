---
title: 'Discrepancy-based Inference for Intractable Generative Models using Quasi-Monte Carlo'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ziang Niu
  - Johanna Meier
  - fx
date: '2023-05-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 'In *Electronic Journal of Statistics*'
publication_short: In *EJS*

abstract: 'Intractable generative models are models for which the likelihood is unavailable but sampling is possible. Most approaches to parameter inference in this setting require the computation of some discrepancy between the data and the generative model. This is for example the case for minimum distance estimation and approximate Bayesian computation. These approaches require sampling a high number of realisations from the model for different parameter values, which can be a significant challenge when simulating is an expensive operation. In this paper, we propose to enhance this approach by enforcing "sample diversity" in simulations of our models. This will be implemented through the use of quasi-Monte Carlo (QMC) point sets. Our key results are sample complexity bounds which demonstrate that, under smoothness conditions on the generator, QMC can significantly reduce the number of samples required to obtain a given level of accuracy when using three of the most common discrepancies: the maximum mean discrepancy, the Wasserstein distance, and the Sinkhorn divergence. This is complemented by a simulation study which highlights that an improved accuracy is sometimes also possible in some settings which are not covered by the theory.'


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
    url: https://arxiv.org/abs/2106.11561

url_pdf: ''
url_code: 
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
