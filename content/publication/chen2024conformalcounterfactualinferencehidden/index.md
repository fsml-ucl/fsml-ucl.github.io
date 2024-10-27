---
title: 'Conformal Counterfactual Inference under Hidden Confounding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - hudson
  - Ruocheng Guo
  - Jean-François Ton
  - Yang Liu

date: '2024-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Knowledge Discovery and Data Mining*
publication_short: in *KDD 2024*

abstract: 'Personalized decision making requires the knowledge of potential outcomes under different treatments, and confidence intervals about the potential outcomes further enrich this decision-making process and improve its reliability in high-stakes scenarios. Predicting potential outcomes along with its uncertainty in a counterfactual world poses the foundamental challenge in causal inference. Existing methods that construct confidence intervals for counterfactuals either rely on the assumption of strong ignorability, or need access to un-identifiable lower and upper bounds that characterize the difference between observational and interventional distributions. To overcome these limitations, we first propose a novel approach wTCP-DR based on transductive weighted conformal prediction, which provides confidence intervals for counterfactual outcomes with marginal converage guarantees, even under hidden confounding. With less restrictive assumptions, our approach requires access to a fraction of interventional data (from randomized controlled trials) to account for the covariate shift from observational distributoin to interventional distribution. Theoretical results explicitly demonstrate the conditions under which our algorithm is strictly advantageous to the naive method that only uses interventional data. After ensuring valid intervals on counterfactuals, it is straightforward to construct intervals for individual treatment effects (ITEs). We demonstrate our method across synthetic and real-world data, including recommendation systems, to verify the superiority of our methods compared against state-of-the-art baselines in terms of both coverage and efficiency.'


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
    url: https://arxiv.org/abs/2405.12387

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
