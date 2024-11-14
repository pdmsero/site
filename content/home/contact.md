---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 110

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Add contact details
  email: your.email@example.com
  phone: 888 888 88 88
  
  # Email form provider
  form:
    provider: netlify
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true
  
design:
  columns: '2'
---
