---
title: 'Approximate Top-k for Increased Parallelism'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - oscar
  - Luka Ribar
  - Alberto Cattaneo
  - Luke Hudlass-Galley
  - Douglas Orr

date: '2024-12-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: 'Efficient Natural Language and Speech Processing workshop (ENLSP) at NeurIPS 2024'
publication_short: 'ENLSP @ NeurIPS 2024'

abstract: 'We present an evaluation of bucketed approximate top-k algorithms. Computing top-k exactly suffers from limited parallelism, because the k largest values must be aggregated along the vector, thus is not well suited to computation on highly-parallel machine learning accelerators. By relaxing the requirement that the top-k is exact, bucketed algorithms can dramatically increase the parallelism available by independently computing many smaller top-k operations. We explore the design choices of this class of algorithms using both theoretical analysis and empirical evaluation on downstream tasks. Our motivating examples are sparsity algorithms for language models, which often use top-k to select the most important parameters or activations. We also release a fast bucketed top-k implementation for PyTorch.'


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
    url: https://arxiv.org/abs/2412.04358

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
