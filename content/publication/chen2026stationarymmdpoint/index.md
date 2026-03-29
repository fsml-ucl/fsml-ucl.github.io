---
title: 'Stationary MMD Points'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - huson
  - Toni Karvonen
  - Heishiro Kanagawa,
  - fx
  - Chris. J. Oates
date: '2025-05-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: 'Approximation of a target probability distribution using a finite set of points is a problem of fundamental importance in numerical integration. Several authors have proposed to select points by minimising a maximum mean discrepancy (MMD), but the non-convexity of this objective typically precludes global minimisation. Instead, we consider the concept of \emph{stationary points of the MMD} which, in contrast to points globally minimising the MMD, can be accurately computed. Our main contributions are two-fold and theoretical in nature. We first prove the (perhaps surprising) result that, for integrands in the associated reproducing kernel Hilbert space, the numerical integration error of stationary MMD points vanishes \emph{faster} than the MMD. Motivated by this \emph{super-convergence} property, we consider MMD gradient flows as a practical strategy for computing stationary points of the MMD. We then prove that MMD gradient flow can indeed compute stationary MMD points, based on a refined convergence analysis that establishes a novel non-asymptotic finite-particle error bound.'


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
    url: https://arxiv.org/abs/2505.20754

url_pdf: ''
url_code: https://github.com/hudsonchen/stationary_mmd
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
