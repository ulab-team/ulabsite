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
      
    design:
      spacing:
        padding: [15, 15, 15, 15]
        margin: [10, 10, 10, 10]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "Grey"


  - block: hero
    content:
      title: |
        About us
      image:
        filename: street_collage.JPG
      text: |
        <br>
      
        **Urban Analytics and Interventions Research Lab** aims to apply urban analytics to longitudinal data generated from built environment interventions (e.g., open space, new metro, urban renewal). Using rigorous research designs such as natural experiments, we are interested in collecting practice-based evidence of the social and health impacts imposed by urban planning and design. With the scientific evidence and situated knowledge in local contexts, we aim to facilitate evidence-based policies and practices in place-making.


  - block: collection
    id: res
    content:
      title: Research Areas
      subtitle: ''
      text: We are interdisciplinary. uLab's research employs urban analytics, empirical social science, human geography, architecture, and urban studies and planning.
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
      sort_by: 'Title'
      sort_ascending: True
    design:
      spacing:
        padding: [15, 15, 15, 15]
        margin: [20, 20, 20, 20]

      # Choose a listing view
      view: showcase
      flip_alt_rows: false
      columns: '3'
  
  - block: collection
    content:
      title: Featured Publications

      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
      text: |
        {{% cta cta_link="./publication/" cta_text="See full record →" %}}  
    design:
      view: citation
      columns: '3'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
