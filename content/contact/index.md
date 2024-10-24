---
title: Contact
date: 2024-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Welcome to contact us!
      email: qxu@cse.cuhk.edu.hk
      phone: 888 888 88 88
      address:
        street: The Chinese University of Hong Kong
        city: Hong Kong
        region: ShaTin
        postcode: '999077'
        country: China
        country_code: CN
      coordinates:
        latitude: 22°25'9"N
        longitude: 114°12'24"E
      directions: Ho Sin-Hang Engineering Building
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'xxx'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
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
          filename: contact.jpg
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
