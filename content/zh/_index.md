---
# Leave the homepage title empty to use the site title
#<br>
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 云计算与智能信息处理实验室
        content: <font face=""><strong>C</strong>loud <strong>C</strong>omputing and <strong>I</strong>ntelligent</br>Information <strong>P</strong>rocessing Laboratory</font>
        align: left
        background:
          image:
            filename: team3.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 联系我们
          url: ../contact/
      # - title: 组会 & 讨论 ☕️
      #   content: '在组内分享你的知识'
      #   align: left
      #   background:
      #     image:
      #       filename: contact.jpg
      #       filters:
      #         brightness: 0.7
      #     position: center
      #     color: '#555'
      - title: 云计算与智能信息处理实验室
        content: <font face=""><strong>C</strong>loud <strong>C</strong>omputing and <strong>I</strong>ntelligent</br>Information <strong>P</strong>rocessing Laboratory</font>
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 联系我们
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000


  - block: markdown
    content:
      title: 云计算与智能信息处理实验室
      subtitle: <strong>C</strong>loud <strong>C</strong>omputing and <strong>I</strong>ntelligent Information <strong>P</strong>rocessing Laboratory (CCIP Lab)
      fontsize: ""
      url: author/徐俊刚/
      image:
        filename: team2-16-9.jpg
        width: 100%
        height: 100%
      text: |
        <strong>云计算与智能信息处理实验室</strong>成立于2010年1月，隶属于中国科学院大学计算机科学与技术学院，拥有自由开放的学术氛围和国际前沿的研究方向。实验室主任为徐俊刚教授。
        实验室主要的研究方向：
        （1）机器学习与深度学习；
        （2）大数据管理；
        （3）量化投资；
        （4）云计算。
        实验室本着“博学笃志，格物明德”的国科大精神，坚持“创新、求实、开放、合作”的理念，不断开拓进取，致力成为国内一流的科研和人才培养基地。
      # text: |
      #   <div style="display:flex;justify-content:center;align-items:center;column-gap:30px">

      #   <a href="/research">
      #   <figure><div class="d-flex justify-content-center"><div class="w-100">
      #   <img alt="" src="/media/team2-16-9.jpg"  height="500" loading="lazy" data-zoomable="" class="medium-zoom-image">
      #   </div></div></figure>
      #   </a>

      #   <font>
      #   <strong>云计算与智能信息处理实验室</strong>成立于2010年1月，隶属于中国科学院大学计算机科学与技术学院，拥有自由开放的学术氛围和国际前沿的研究方向。实验室主任为徐俊刚教授。
      #   实验室主要的研究方向：
      #   （1）机器学习与深度学习；
      #   （2）大数据管理；
      #   （3）量化投资；
      #   （4）云计算。
      #   实验室本着“博学笃志，格物明德”的国科大精神，坚持“创新、求实、开放、合作”的理念，不断开拓进取，致力成为国内一流的科研和人才培养基地。
      #   <a href="/research">阅读更多...</a>
      #   </font>
      #   </div>
    design:
      columns: '1'
      tag: intro
  - block: markdown
    content:
      fontsize: ""
      url: author/徐俊刚/
      image:
        filename: xjg.jpg
        width: 100%
        height: 100%
      text:
        徐俊刚 中国科学院大学计算机科学与技术学院教授，博士生导师，CCIP实验室主任，中国科学院大学第六届学位评定委员会计算机与控制学位评定委员会委员，计算机科学与技术学院教学委员会委员，计算机科学与技术学院“深度学习”课程首席教授。2003年博士毕业于中国科学院软件研究所，2005年清华大学计算机科学与技术系博士后出站。研究领域包括深度学习、自动机器学习和多模态智能分析等，主持国家科技支撑计划课题、国家自然科学基金面上项目、北京市科技计划课题、北京市自然科学基金面上项目等科研项目多项，发表论文100余篇。现为国家科技专家库专家，北京市科学技术委员会、中关村科技园区管理委员会专家。目前任中国人工智能学会智能服务专业委员会常务委员，中国计算机学会人工智能与模式识别专业委员会执行委员、数据库专业委员会执行委员和自然语言处理专业委员会执行委员。讲授的“深度学习”课程被评为2021年中国科学院大学“校级优秀研究生课程”，个人荣获2016年“中国科学院朱李月华优秀教师奖”。
    design:
      columns: '1'
      tag: intro
  # - block: markdown
  #   content:
  #     image:
  #       filename: xjg.jpg
  #     text:
  #       <div style="display:flex;justify-content:center;align-items:center;column-gap:30px"><a href="/author/徐俊刚/"><figure><div class="d-flex justify-content-center"><div class="w-100">
  #       <img alt="" src="/media/xjg.jpg" width="500" height="1600" loading="lazy" data-zoomable="" class="medium-zoom-image">
  #       </div></div></figure></a>
  #       <font>
  #       徐俊刚 中国科学院大学计算机科学与技术学院教授，博士生导师，CCIP实验室主任，中国科学院大学第六届学位评定委员会计算机与控制学位评定委员会委员，计算机科学与技术学院教学委员会委员，计算机科学与技术学院“深度学习”课程首席教授。2003年博士毕业于中国科学院软件研究所，2005年清华大学计算机科学与技术系博士后出站。研究领域包括深度学习、自动机器学习和多模态智能分析等，主持国家科技支撑计划课题、国家自然科学基金面上项目、北京市科技计划课题、北京市自然科学基金面上项目等科研项目多项，发表论文100余篇。现为国家科技专家库专家，北京市科学技术委员会、中关村科技园区管理委员会专家。目前任中国人工智能学会智能服务专业委员会常务委员，中国计算机学会人工智能与模式识别专业委员会执行委员、数据库专业委员会执行委员和自然语言处理专业委员会执行委员。讲授的“深度学习”课程被评为2021年中国科学院大学“校级优秀研究生课程”，个人荣获2016年“中国科学院朱李月华优秀教师奖”。
  #       <a href="/author/徐俊刚/">阅读更多...</a></font></div>
  #   design:
  #     columns: '1'
  #     tag: intro
  - block: collection
    content:
      title: 新闻动态
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
      archive:
        enable: true
    design:
      view: compact
      columns: '2'
  

  - block: collection
    content:
      title: 论文动态
      text: 
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
      archive:
        enable: true
    design:
      view: citation
      columns: '2'


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="遇见团队 →" %}}
    design:
      columns: '1'
      background:
        image:
          filename: footer1.jpg
          filters:
            brightness: 0.3
        position: right
        color: '#666'
---
