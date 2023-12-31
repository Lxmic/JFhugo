---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: 'Hello, everyone!' 
      image:
        filename: 'header.jpg'

      text: |-
        Welcome to Jianfeng Jin's personal website
      cta:
        label: '<i class="fa-solid fa-id-card"></i> Check my CV here'
        url: uploads/resume.pdf
      #cta_alt:
        #label: Ask a question
        #url: https://discord.gg/z8wNYzb
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
        Please contact me via the email
        (lxm0404@zju.edu.cn).
      # Contact (add or remove contact options as necessary)
      email: lxm0404@zju.edu.cn
      # phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 866 Yuhangtanglu
        city: Hangzhou
        region: Zhejiang, China
        #postcode: '94305'
        #country: United States
        #country_code: US
      office_hours:
        - 'Monday-Friday 10:00 to 20:00'
        - 'Saturday-Sunday 13:00 to 22:00'
      # contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
      columns: '2'
---
