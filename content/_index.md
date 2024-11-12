---
# Leave the homepage title empty to use the site title
title: 
date: 2024-11-12
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: |
        About us
      image:
        filename: aesthetic_viz.png
      text: |
        <br>
        
        The **Urban Analytics and Interventions Research Lab** brings the state of the art urban causal research since its founding in 2021.
  
    - block: cta-image-paragraph
      id: about
      content:
       items:
        - title: About us
          text: A policy research led by Dr Guibo Sun. dsggf srtrt sdfd ytygfd aerth gfdrgre.
          # Upload image to `assets/media/` and reference the filename here
          image: bg3.jpg
          button:
            text: More info
            url: about/

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
