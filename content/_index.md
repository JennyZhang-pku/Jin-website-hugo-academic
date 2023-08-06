---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-04
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Stata
          description: 90%
          icon: chart-line
          icon_pack: fas
        - name: Matlab
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to email me if you have any comment or suggestions!
      # Contact (add or remove contact options as necessary)
      email: jin.zhang@emory.edu
      phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 1509 Clifton Road
        city: Atlanta
        region: GA
        postcode: '30322'
        country: United States
        country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
        # - 'Monday 10:00 to 13:00'
        # - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Jellyfish_Z007
          link: https://twitter.com/Twitter
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
      columns: '2'
---
