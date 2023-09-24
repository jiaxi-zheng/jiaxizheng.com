---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: jiaxiz@andrew.cmu.edu
  address:
    street: 5000 Forbes Ave, , PA 15213
    city: Pittsburgh 
    region: 
    postcode: '15213'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.443504'
    longitude: '-79.941571'
  directions: NSH

design:
  columns: '2'
---
