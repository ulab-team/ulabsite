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
      text:  | 
      <br>
      A research lab advancing urban intelligibility
      <br />
        <div>
        <ul class="network-icon" aria-hidden="true">
          <li>
            <a itemprop="sameAs" href="mailto:text@example.com">
              <i class="fas fa-envelope small-icon"></i>
            </a>
          </li>
          <li>
            <a itemprop="sameAs" href="http://twitter.com/ulab_hku" target="_blank" rel="noopener">
              <i class="fab fa-x-twitter small-icon"></i>
            </a>
          </li>
          <li>
            <a itemprop="sameAs" href="https://www.linkedin.com/company/example/" target="_blank" rel="noopener">
              <i class="fab fa-linkedin small-icon"></i>
            </a>
          </li>   
        </ul>
        </div>
      
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

  
  - block: collection
    content:
      title: Featured Publications
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        featured_only: true
      text: |
        {{% cta cta_link="./publication/" cta_text="See full record →" %}}  
    design:
      view: citation

  - block: collection
    content:
      title: Recent News
      count: 3
      filters:
        folders:
          - news
      text: uLab curates a vibrant research community through institutional connections.
    design:
      view: compact

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact Us
      text: |
        We welcome intellectual exchange with scholars, collaboration with practitioners, industry leaders, and training for students and early career researchers (predocs and PhD students)
      email: test@example.org
      address: 
        street: ''
        city: ''
        country: ''
        country_code: ''

      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: false

    design:
      columns: '2'
---
