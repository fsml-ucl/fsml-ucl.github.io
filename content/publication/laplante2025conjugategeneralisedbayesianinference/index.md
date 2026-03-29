---
title: 'Conjugate Generalised Bayesian Inference for Discrete Doubly Intractable Problems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - william
  - matias
  - jeremias
  - Andrew Duncan
  - fx
date: '2025-11-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: 'Doubly intractable problems occur when both the likelihood and the posterior are available only in unnormalised form, with computationally intractable normalisation constants. Bayesian inference then typically requires direct approximation of the posterior through specialised and typically expensive MCMC methods. In this paper, we provide a computationally efficient alternative in the form of a novel generalised Bayesian posterior that allows for conjugate inference within the class of exponential family models for discrete data. We derive theoretical guarantees to characterise the asymptotic behaviour of the generalised posterior, supporting its use for inference. The method is evaluated on a range of challenging intractable exponential family models, including the Conway-Maxwell-Poisson graphical model of multivariate count data, autoregressive discrete time series models, and Markov random fields such as the Ising and Potts models. The computational gains are significant; in our experiments, the method is between 10 and 6000 times faster than state-of-the-art Bayesian computational methods.'


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
    url: https://arxiv.org/abs/2511.23275

url_pdf: ''
url_code: https://github.com/williamlaplante/DSM
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
