---
title: "A General Method for Calibrating Stochastic Radio Channel Models with Kernels"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ayush
  - fx
  - Troels Pedersen
date: '2022-10-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 'In *IEEE Transactions on Antennas and Propagation*'
publication_short: In *IEEE Transactions on Antennas and Propagation*

abstract: "Calibrating stochastic radio channel models to new measurement data is challenging when the likelihood function is intractable. The standard approach to this problem involves sophisticated algorithms for extraction and clustering of multipath components, following which, point estimates of the model parameters can be obtained using specialized estimators. We propose a likelihood-free calibration method using approximate Bayesian computation. The method is based on the maximum mean discrepancy, which is a notion of distance between probability distributions. Our method not only by-passes the need to implement any high-resolution or clustering algorithm, but is also automatic in that it does not require any additional input or manual pre-processing from the user. It also has the advantage of returning an entire posterior distribution on the value of the parameters, rather than a simple point estimate. We evaluate the performance of the proposed method by fitting two different stochastic channel models, namely the Saleh-Valenzuela model and the propagation graph model, to both simulated and measured data. The proposed method is able to estimate the parameters of both the models accurately in simulations, as well as when applied to 60 GHz indoor measurement data."


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
    url: https://arxiv.org/abs/2012.09612

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
