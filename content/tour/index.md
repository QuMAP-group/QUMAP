---
title: Tour
date: 2022-10-24

type: landing

sections:

  - block: gallery
    content:
      title: "test
      items:
        - image:
            filename: "icon.png"
        - image:
            filename: "icon.png"
    design:
      columns: "2"

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        
      - title: Superfluids
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
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
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
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
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
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
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
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

---
