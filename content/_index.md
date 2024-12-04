---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: "Welcome to Microrobotic Biomedical Systems group 👋"
      text: |
        We engineer intelligent microrobots for biomedical applications in targeted drug delivery, microsurgery, detoxification, and diagnostics by advancing micro- and nanofabrication as well as ultrasound technologies. To realize their full potential, medical microrobots have to master locomotion in complex biofluidic environments, wireless actuation and control, precise imaging and localization, or effective drug/cargo delivery. We overcome these challenges by incorporating biologically-inspired adaptive capabilities into microrobotic agents and utilize lab-on-a-chip and microfluidic systems to validate biological and therapeutic functions. We thus bridge the gap between biomedical research and clinical applications to propel medical microrobots to the forefront of modern healthcare.
      image:
        filename: welcome.jpg
        size: contain
        position: left


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
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Papers
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
