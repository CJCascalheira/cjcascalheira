---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact Cory
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
      captcha: true

  # Contact details (edit or remove options as required)
  email:
  phone: 1-575-323-1272
  address:
    street: 1220 Stewart St
    city: Las Cruces
    region: NM
    postcode: '88001'
    country: United States
    country_code: US
  coordinates:
    latitude: '32.28007'
    longitude: '-106.75171'
  directions: The CEP office is on the 2nd floor.
  office_hours:
    - 'Tuesday 08:00 to 12:00'
  appointment_url: 'https://calendly.com/cjcascalheira'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/CJCascalheira'

design:
  columns: '2'
---
