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
  email: test@example.org
  address:
    street: 450 Serra Mall
    city: dalian 
    region: Ganjingzi
    postcode: '116026'
    country: China
    country_code: zh
  coordinates:
    latitude: '38.8713'
    longitude: '121.5324'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2


design:
  columns: '2'
---
