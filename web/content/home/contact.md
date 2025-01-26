---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

#content:
content:
  form:
    provider: formspree
    formspree:
      id: mqkvjwge
      captcha: true # By default false
      captcha_key: 6LcGKQ0pAAAAAN9ElVsgjBixhHw0eKCm5FCG1c8I 
      # From https://www.google.com/recaptcha/admin . Use v2 Checkbox

  # Automatically link email and phone or display as text?
  #autolink: true

  # Email form provider
  # form: 
  # provider: netlify
   #  formspree:
   #    id:
   #  netlify:
      # Enable CAPTCHA challenge to reduce spam?
    #   captcha: false

  # Contact details (edit or remove options as required)
  #email: dkazibwe@deakin.edu.au
  phone: (202)713-1602
  address:
    street: 
    city: Washington
    region: D.C
    postcode: '20037'
    country: United States
    country_code: US
  coordinates:
    latitude: '38.89917'
    longitude: '-77.04142'
  directions: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: _dkazibwe
      link: 'https://twitter.com/_dkazibwe'

      

design:
  columns: '2'
---
