---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome_original.jpg
            filters:
              brightness: 0.3
          position: right
          color: '#666'
      - title: AI-Native EDA
        content: ' Opportunities and Challenges of Large Circuit Models'
        align: left
        background:
          image:
            filename: ai_native_eda.png
            filters:
              brightness: 0.35
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: markdown
    design:
      background:
        image:
          filename: welcome.jpg
          filters:
            brightness: 0.9
          # size: cover
          # position: center
          size: contain
          position: top
          parallax: true
          text_color_light: true
    content:
      # title: |
      #   <font size="9" style="color: rgba(255, 255, 255, 0.99);">
      #   CURE Lab Research Group
      #   </font>
      # image:
      #   filename: welcome.jpg
      text: |
        <div style="background-color: rgba(0, 0, 0, 0.65);">
        <p style="text-align: center">
        <font size=9px style="color: rgba(255, 255, 255, 1);">
        CURE Lab Research Group
        </font></p>
        <font size=4px style="color: rgba(255, 255, 255, 1);">
        At the <u>CU</u>HK <u>RE</u>liable Computing laboratory (CURE Lab.), our core research methodology is rooted in creating innovative solutions that directly tackle the limitations of state-of-the-art computing technologies. Currently, we are passionately committed to the exploration and advancement of artificial intelligence across a variety of cutting-edge directions:
        <br/>
        ✨ AI-Native EDA
        <br/>
        ✨ Image&Video Generation 
        <br/>
        ✨ Time Series
        <br/>
        We are continue to work on the safety and security aspects of AI, developing robust AI models that can withstand adversarial attacks and operate reliably even under uncertain or volatile conditions.
        </font> </div>
---
