---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact
active: true  # Activate this widget? true/false
# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact Us
subtitle:

content:
  # Contact (edit or remove options as required)
  email: info@geogroup.ai
  phone:
  address:
    #street:
	city:  Mansourieh
	region: Beirut
	postcode: '11 828'
	country: Lebanon
	country_code: LB
  coordinates:
	latitude: '33.8577207'
	longitude: '35.5676237'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'

  contact_links:
  - icon: twitter
    icon_pack: fab
    name: Twitter
    link: https://twitter.com/AliJGhandour
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
      captcha: true

  
design:
  columns: '2'
---
