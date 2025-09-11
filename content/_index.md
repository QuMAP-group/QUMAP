---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

sections:
  - block: hero
    id: homepage-banner
    content:
      title: ""        # leave blank if you just want the image
      text: ""         # leave blank
      image:
        filename: "Banner.jpg"   # your long, thin image
    design:
      align: center       # text alignment; irrelevant if no text
      height: full        # makes the hero fill the screen vertically
      width: full
      overlay_opacity: 0  # optional, removes dark overlay


  - block: slider
    content:
      slides:
      - title: Welcome to the QuMAP Research Group
        content: 'Take a look at what we are working on...'
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: Dark Matter Detection
        content: 'details'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#dmd'

      - title: Superfluids
        content: 'details'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#Superfluids'

      - title: New detection mechanism
        content: 'details'
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#newdetection'
        
      - title: New materials
        content: 'details'
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#newmaterials'
        
      - title: AI Design
        content: 'details'
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#AI'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: hero
    id: dmd
    content:
      title: "Dark Matter Detection"
      subtitle: "subtitle"
      text: |
        Details here
      image:
        filename: "icon.png"
    design:
      align: left   # text on the left, image on the right

  - block: hero
    id: Superfluids
    content:
      title: "Superfluids"
      subtitle: "subtitle"
      text: |
        Details here
      image:
        filename: "icon.png"
    design:
      align: left   # text on the left, image on the right

  - block: hero
    id: newdetection
    content:
      title: "New Detection Mechanism"
      subtitle: "subtitle"
      text: |
        Details here
      image:
        filename: "icon.png"
    design:
      align: right   # text on the left, image on the right

  - block: hero
    id: newmaterials
    content:
      title: "New Materials"
      subtitle: "subtitle"
      text: |
        Details here
      image:
        filename: "icon.png"
    design:
      align: right   # text on the left, image on the right

  - block: hero
    id: AI
    content:
      title: "AI Design"
      subtitle: "subtitle"
      text: |
        Details here
      image:
        filename: "icon.png"
    design:
      align: right   # text on the left, image on the right
    




  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          text_color_light: true

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
