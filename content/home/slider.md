---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: 250px
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: 'It is official now!🎉'
      content: 'GEOAI group ranked 4th in the "NASA Harvest Field Boundary Detection Challenge" out of 730 participants <a href="https://github.com/geoaigroup/nasa_harvest_boundary_detection_challenge" target=_blank>[Code]</a>.'
      align: center
      background:
        position: left
        color: '#FFFFFF' #An HTML color value.
        brightness: 0.7
        media: welcome.png
        fit: cover
    - title: 'GeoUrban-AI Tool'
      content: '<a href="http://geoai.cnrs.edu.lb/urbanmodels/" target=_blank> GeoUrban-AI</a> tool has been extremley welcomed by the community and received enormous amount of positive feedback so far.'
      align: center
      background:
        position: left
        color: '#555' #An HTML color value.
        brightness: 0.7
        media: contact.jpg
        fit: cover
    - title: ECRS2023👏
      content: '<a href="https://github.com/geoaigroup/geoai-ecrs2023" target=_blank> Repo </a>with details about our 4 papers accepted at ECRS 2023.'
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: welcome.png
        fit: cover
    - title: Openings!
      content: 'Internship and graduate thesis openings available. Send resume and cover letter👇'
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: /#contact
---