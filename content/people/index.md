---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigator
        - Project Assistant
        - Postdocs
        - PhD Students
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: markdown
    content:
      title: ""
      text: |
        <div class="group-photos-row">
          <img src="/media/group_photos/IMG_0461.jpg" alt="Group photo 1">
          <img src="/media/group_photos/IMG_2131.jpg" alt="Group photo 2">
          <img src="/media/group_photos/IMG_5655.JPG" alt="Group photo 3">
          <img src="/media/group_photos/IMG_6043.jpg" alt="Group photo 4">
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '0', '0']
---