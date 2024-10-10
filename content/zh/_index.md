---
# Leave the homepage title empty to use the site title
#<br>
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: 
        |
      image: 
        filename: welcome.jpg
      text: |
        **云计算与智能信息处理实验室**（CCIP Lab）
        成立于2010年1月，隶属于中国科学院大学计算机科学与技术学院，拥有自由开放的学术氛围和国际前沿的研究方向。实验室主任为徐俊刚教授。<br>
        实验室主要的研究方向：
        （1）机器学习与深度学习；（2）大数据管理；（3）量化投资；（4）云计算。<br>
        实验室本着“博学笃志，格物明德”的国科大精神，坚持“创新、求实、开放、合作”的理念，不断开拓进取，致力成为国内一流的科研和人才培养基地。 ([更多信息](/post/24-09-01-introduction/))
  
  - block: collection
    content:
      title: 近期动态
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
      title: 近期著作
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
