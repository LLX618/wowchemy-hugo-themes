---
title: 联系我们
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-

      email: huzhenzhong@tsinghua.edu.cn
      # phone: 888 888 88 88
      address:
        street: 南山区桃源街道2279号
        city: 深圳市
        region: 广东省
        postcode: '518073'
        country: China
        country_code: China
      coordinates:
        latitude: '22.5921'
        longitude: '113.9695'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
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
