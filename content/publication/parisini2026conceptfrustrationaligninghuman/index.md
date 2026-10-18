---
title: 'Concept frustration: Aligning human concepts and machine representations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Enrico Parisini
  - Christopher J. Soelistyo
  - ahab
  - alessandro
  - Christopher R.S. Banerji
  
date: '2026-03-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2026*
publication_short: In *NeurIPS*


abstract: "Aligning human-interpretable concepts with the internal representations learned by modern machine learning systems remains a central challenge for interpretable AI. We introduce a geometric framework for comparing supervised human concepts with unsupervised intermediate representations extracted from foundation model embeddings. Motivated by the role of conceptual leaps in scientific discovery, we formalise the notion of concept frustration: a contradiction that arises when an unobserved concept induces relationships between known concepts that cannot be made consistent within an existing ontology. We develop task-aligned similarity measures that detect concept frustration between supervised concept-based models and unsupervised representations derived from foundation models, and show that the phenomenon is detectable in task-aligned geometry while conventional Euclidean comparisons fail. Under a linear-Gaussian generative model we derive a closed-form expression for Bayes-optimal concept-based classifier accuracy, decomposing predictive signal into known-known, known-unknown and unknown-unknown contributions and identifying analytically where frustration affects performance. Experiments on synthetic data and real language and vision tasks demonstrate that frustration can be detected in foundation model representations and that incorporating a frustrating concept into an interpretable model reorganises the geometry of learned concept representations, to better align human and machine reasoning. These results suggest a principled framework for diagnosing incomplete concept ontologies and aligning human and machine conceptual reasoning, with implications for the development and validation of safe interpretable AI for high-risk applications."


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
    url: https://arxiv.org/abs/2603.29654

url_pdf: ''
url_code: https://github.com/CRSBanerji/concept-frustration
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
