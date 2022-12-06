---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)
 email: m.diluca@bham.ac.uk
  address:
    street: Edgbaston
    city: Birmingham
    region: WM
    postcode: 'B15 2TT'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '52.44972114103527'
    longitude: '-1.932553875570192'
  directions: Enter Hills Building and take the stairs to the Symonlab  on Floor 2
  office_hours:
    - 'Monday to Friday 10:00 to 18:00'
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
---

The project is run at the University of Birmingham in the Symonlab
