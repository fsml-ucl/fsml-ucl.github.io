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
      text: |-
        {{% callout note %}}
        See the full list [here](./publications/).
        {{% /callout %}}
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      columns: '2'
      view: citation
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
