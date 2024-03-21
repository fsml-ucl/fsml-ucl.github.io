---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: ucl.jpg
  #         parallax: true
  #         position: bottom
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['100px', '0', '100px', '0']
  - block: about.avatar
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: people
    id: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Permanent Academics
        - Postdoctoral Researchers
        - PhD Students
        - Visiting Researchers
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: community/news
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      count: 5
      # text: |-
      #   {{% callout note %}}
      #   See the full list [here](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Major Research Funding'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2027-02-28'
          date_start: '2024-03-01'
          description: ''
          icon: 
          organization: EP/Y022300/1
          organization_url: https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/Y022300/1
          title: 'EPSRC New Investigator Award. Project on ‘Transfer Learning for Monte Carlo Methods’ (PI: Briol)'
          url: ''
        - certificate_url: 
          date_end: '2025-02-28'
          date_start: '2024-03-01'
          description: ''
          icon: 
          organization: EP/Y011805/1
          organization_url: https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/Y011805/1
          title: 'EPSRC Small Grant in the Mathematical Sciences, Project on “Robust Foundations for Bayesian Inference” (PI: Briol, co-I: Knoblauch)'
          url: ''
        - certificate_url: 
          date_end: '2025-12-31'
          date_start: '2024-01-01'
          description: ''
          icon: 
          organization: UKRI
          organization_url: 
          title: 'UKRI/Turing Project “Digital Twin Handbook” (co-I: Briol)'
          url: ''
        - certificate_url: 
          date_end: '2025-06-30'
          date_start: '2022-07-01'
          description: ''
          icon: 
          organization: EP/W005859/1
          organization_url: https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/W005859/1
          title: 'EP/W005859/1: EPSRC Fellowship, Project on “Optimisation-centric Generalisations of Bayesian Inference” (PI: Knoblauch)'
          url: ''
        - certificate_url: 
          date_end: '2022-12-31'
          date_start: '2021-01-01'
          description: ''
          icon: 
          organization: Biometrika
          organization_url: 
          title: 'Biometrika fellowship: “Generalising Bayesian Inference” (PI: Knoblauch)'
          url: ''
        - certificate_url: 
          date_end: '2019-12-31'
          date_start: '2019-01-01'
          description: ''
          icon: 
          organization: Amazon
          organization_url: https://www.ucl.ac.uk/mathematical-physical-sciences/news/2020/jul/ucl-statistical-science-lecturer-receives-2019-amazon-research-award#:~:text=Dr%20François%2DXavier%20Briol%20of,support%20of%20each%20research%20project.
          title: 'Amazon Research Award: Project on “Transfer Learning for Numerical Integration in Expensive Machine Learning Systems” (PI: Briol)'
          url: ''
        
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      address:
        street: 1-19 torrington place
        city: London
        region: 
        postcode: 'WC1E 7HB'
        country: United Kingdom
        country_code: UK
      directions: 
      office_hours:
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '51.521906'
        longitude: '-0.134348'  
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
