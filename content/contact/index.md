---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Contact info for the group.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: Michael Smith Building, Dover St  
        city: Manchester
        region: Greater Manchester
        postcode: 'M13 9NT'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '53.463848'
        longitude: '-2.227320'  
      office_hours:
        - 'Monday - Friday 9:00 to 17:00'

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

