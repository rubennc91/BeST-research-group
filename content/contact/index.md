---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: BeST - Bioengineering Systems and Technologies Research Group
      text: |-
        Welcome to the contact page of the Bioengineering Systems and Technologies (BeST) Research Group at Universidad Rey Juan Carlos!
        
      email: antonio.ama@urjc.es
      phone: +34 91 123 4567
      address:
        street: Tulipán Street, 0
        city: Móstoles
        region: Madrid
        postcode: '28933'
        country: Spain
        country_code: ES
      coordinates:
        latitude: '40.335548'
        longitude: '-3.877743'
      directions: Departamental II - Office 166
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
          captcha: true
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
