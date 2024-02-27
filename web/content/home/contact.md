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
  phone: 61416956540
  address:
    street: 28/60 Elgar Rd
    city: Burwood
    region: VIC
    postcode: '3125'
    country: Australia
    country_code: AUS
  coordinates:
    latitude: '-37.846016'
    longitude: '145.110368'
  directions: EA Building, Level 2, EA 2.40
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: _dkazibwe
      link: 'https://twitter.com/_dkazibwe'

      

design:
  columns: '2'
---
