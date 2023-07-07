---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 国家重点研发计划项目<br>建筑与市政公用设施智慧运维理论与方法<br>
      subtitle: <font size=5>建筑与市政公用设施智慧运维性态全息快速感知与多源异构数据融合
    design:
      columns: '1'
      background: 
        color: '#F2F2F2'

    
  - block: hero
    content:
      title: |
        
      image:
        filename: jishuluxian.png
      text: |
        <br>
        <div style="text-justify:auto">本课题为国家重点研发计划项目<b>建筑与市政公用设施智慧运维理论与方法（2022YFC3801100）</b>中的子课题二，针对建筑与市政公用设施多源异构运维大数据的<b>统一编码</b>与<b>关联融合</b>机制，研究基于分布式边缘计算与网联架构的多源异构运维数据<b>快速感知</b>和<b>近实时传输技术。</b></div>


  
  - block: collection
    content:
      title: 专题详情
      subtitle:
      text:
      count: 8
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
      view: showcase
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---