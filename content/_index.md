---
# Leave the homepage title empty to use the site title
title:
date: 2024-05-25
type: landing

sections:
  - block: markdown
    design:
      background:
        image:
          filename: welcome.jpg
          filters:
            brightness: 0.9
          size: cover
          position: center
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
      # background:
      #   image: 
      #     filename: coders.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      # spacing:
      #   padding: ['20px', '0', '20px', '0']
      # css_class: fullscreen

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
      title: Graduate and PostDoc Researchers
      text: |
        <div style="text-align: center;">
          <img src="/Users/bianyuxuan/Desktop/PhD/Docs/CUHK PhD/cure_lab_web_own/content/authors/QiangXu/avatar.jpg" alt="Prof. Qiang Xu" style="width:100px; border-radius:50%;">
          <p><strong>Prof.  Qiang Xu</strong><br>Principal Investigator</p>
        </div>
        <div style="display: flex; flex-wrap: wrap; justify-content: center;">
          <div style="margin: 10px; text-align: center;">
            <img src="/Users/bianyuxuan/Desktop/PhD/Docs/CUHK PhD/cure_lab_web_own/content/authors/XuanJu/avatar.jpg" alt="Xuan Ju" style="width:80px; border-radius:50%;">
            <p><a href="#" style="color: #1a73e8;">Xuan Ju</a><br>PhD, started SP'22</p>
          </div>
          <div style="margin: 10px; text-align: center;">
            <img src="/Users/bianyuxuan/Desktop/PhD/Docs/CUHK PhD/cure_lab_web_own/content/authors/XuanJu/avatar.jpg" alt="Xuan Ju" style="width:80px; border-radius:50%;">
            <p><a href="#" style="color: #1a73e8;">Xuan Ju</a><br>PhD, started SP'22</p>
          </div>
          <!-- 添加更多人物 -->
        </div>
    design:
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="People →" %}}
  #   design:
  #     columns: '1'
---
