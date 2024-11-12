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
      title: Urban Analytics and Interventions Research Lab
      text: A research lab advancing urban intelligibility


  - block: hero
    content:
      title: |
        About us
      image:
        filename: aesthetic_viz.png
      text: |
        <br>
      
        The **Urban Analytics and Interventions Research Lab** brings the state of the art urban causal research since its founding in 2021.


  - block: collection
    id: res
    content:
      title: research directions
      subtitle: ''
      text: 'these are our major research directions'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - research
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card
      columns: '3'
  

  
  - block: collection
    content:
      title: Recent Publications
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
