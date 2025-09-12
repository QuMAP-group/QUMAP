---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

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

      - title: Beyond WIMP Dark Matter: From Theory to Detection
        content: 'We investigate how dark matter could have been produced in the early universe and what this means for its fundamental nature. Our research bridges cosmology and experiment, developing new methods to reveal dark matter signatures both in controlled laboratory systems and in the observation of celestial bodies.'
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
          url: '#beyondWIMP'

      - title: Quantum Sensors for sub-GeV Dark Matter
        content: 'Dark matter particles lighter than the proton remain one of the most elusive frontiers. By advancing quantum sensing technologies and superfluid detectors, we aim to probe these ultra-light candidates with unprecedented precision and sensitivity.'
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
          url: '#quantsensor'

      - title: Generative AI for Next-Generation Crystals
        content: 'We harness the power of generative AI to design novel molecular crystals that act as particle detectors. These materials are envisioned to be inexpensive, scalable, and capable of directional sensitivity, opening a new pathway toward dark matter discovery.'
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
          url: '#genAI'
        
      - title: AI for Molecules and Medicine
        content: 'Artificial intelligence is revolutionising how we discover and evaluate molecular properties. Our work applies AI-driven searches to link molecular structure to biological activity, accelerating innovation at the intersection of fundamental science and health applications.'
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
          url: '#AImolmed'
        

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
