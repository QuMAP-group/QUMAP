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
          - Post-Doctoral Researchers
          - PhD Students
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: BannerNew.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
    padding:
      top: 0  
      bottom: 0  
---
