---
title: Contact
date: 2024-11-14

type: landing

sections:
  - block: contact
    content:
      title: Contact Us
      text: |-
        We welcome intellectual exchange with scholars, collaboration with practitioners, industry leaders, and training for students and early career researchers (predocs and PhD students)
      email: test@example.org
      WhatsApp: +852 1234 5678
      address:
        street: Nwe World Tower 1, 18 Queen's Road Central
        city: Central
        region: Hong Kong
        postcode: ''
        country: China
        country_code: HK
      coordinates:
        latitude: '22.280853'
        longitude: '114.157123'
      directions: 
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'

      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: false
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
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
          filename: uLab_logo2.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
