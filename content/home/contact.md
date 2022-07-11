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
    provider: formspree
    formspree:
      id: xrgjwoga
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: duc.nguyenquang@hcmut.edu.vn
  phone: (+84) 898 986 370
  address:
    street: 268 Ly Thuong Kiet
    city: Ward 14
    region: District 10
    postcode: '700000'
    country: Vietnam
    country_code: VN
  coordinates:
    latitude: '10.772856'
    longitude: '106.657753'
  directions: Enter Gate 1, then turn left to the parking area. I am available in VNPT Lab.
  office_hours:
    - 'Morning: 8 a.m. to 12 p.m.'
    - 'Afternoon: 13 p.m. to 17 p.m.'
  appointment_url: 'https://calendly.com/martinakaduc'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/martinakaduc'

design:
  columns: '2'
---
