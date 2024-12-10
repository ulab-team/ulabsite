---
# Leave the homepage title empty to use the site title
title: 
date: 2024-11-12
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: Expertise
      subtitle: ''
      text: |
        **The uLab-Infrastructure** establishes research and practice in essential urban data, new methodologies and causal evidence to extend scientific understandings of social, economic and health outcomes of large-scale interventions in cities. Our work focuses on the sustainable development of new transport infrastructure, urban renewal, and urban experimentation, contributing to healthy, equitable and adaptive cities and communities.
    design:
      columns: '1'

  - block: collection
    id: res
    content:
      title: ''
      subtitle: ''
      # text: We are interdisciplinary. uLab's research employs urban analytics, empirical social science, human geography, architecture, and urban studies and planning.
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
      sort_by: weight
      sort_ascending: True
    design:
      spacing:
        padding: [15, 15, 15, 15]
        margin: [20, 20, 20, 20]

      # Choose a listing view
      view: showcase
      flip_alt_rows: false
---