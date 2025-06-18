---
# Leave the homepage title empty to use the site title
title: 

date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to **GMC**
        content: Advancing Carbon Neutrality and Green Hydrogen via Field-Enhanced Electrolysis.
        align: center
        background:
          image:
            filename: groupimage.jpg
            filters:
              brightness: 0.8
          position: right
          size: contain
          color: '#666'
        link:
          icon: 
          icon_pack: fas
          text: Check our research...
          url: ../tour/

      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.8
          position: center
          size: contain
          color: '#555'
        link:
          icon: enjoy
          icon_pack: fas
          text: latest News
          url: ../post/

      - title:  Field-enhanced (photo)electrocatalysis Lab
        content: ''
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.8
          position: center
          size: contain
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: ture
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: hero
    content:
      title: |
        Green Molecules Conversion Group (GMC)
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Our group is dedicated to advancing electrocatalysis and energy conversion by leveraging external field effects-such as electric and magnetic fields-to boost electrochemical reactions. We focus on developing efficient solutions for green hydrogen production and CO₂ reduction, aiming to contribute to carbon neutrality through innovative field-enhanced catalytic strategies.
  
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
  


  - block: collection
    content:
      title: Latest publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen      
---
