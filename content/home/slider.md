---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: 500px
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: 'it is official now!🎉🤴👏 '
      content: 'GEOAI group ranked 4th in the "NASA Harvest Field Boundary Detection Challenge" out of 730 participants.<br> Our solution is made public via following repo:<br><a href="https://github.com/geoaigroup/nasa_harvest_boundary_detection_challenge" targe=_blank>https://github.com/geoaigroup/nasa_harvest_boundary_detection_challenge</a>'
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: NASAHarvest.jpeg
        fit: cover
    - title: Sci-Net
      content: 'Our new paper "Sci-Net: scale-invariant model for buildings segmentation from aerial imagery" was just published online:<br><a href="https://link.springer.com/article/10.1007/s11760-023-02520-3" target=_blank>https://link.springer.com/article/10.1007/s11760-023-02520-3</a>'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: SciNet.jpeg
        fit: cover
    - title: Openings!
      content: 'GEOAI group has available openings for summer internship and graduate thesis/project. Interested candidates should send resume and cover letter using Contact widget below'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.png
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: (#contact)
---