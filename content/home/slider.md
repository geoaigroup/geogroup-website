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
  interval: 2000

content:
  slides:
    - title: GEOspatial Artificial Intelligence
      content: 'GEOAI is a research group located at the <a href="http://rsensing.cnrs.edu.lb" target="_blank">National Center for Remote Sensing </a> - <a href="http://www.cnrs.edu.lb" target="_blank">CNRS</a> , Lebanon. Our research is focused on AI-assisted mapping spanning various applications, including urban analytics, transportation, waterbodies monitoring and crop-yield estimation. We develop tools integrating deep learning techniques to automate the process of urban features extraction and collect crowd-sourcing data from various sources. Evidence gained from our models and data analysis allows for a robust humanitarian response and provides policymakers and key stakeholders with insights to design tailored regulations and safety countermeasures for urban social good.<br> GEOAI group provides a unique opportunity for geospatial training in a professional research environment in Lebanon. We have hosted more than 40 students at both undergraduate and graduate levels since 2016.</strong>'
      align: left
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.png
        fit: cover
    - title: 'it is official now!🎉 😍 🤴 💪 👏 🎈'
      content: 'GEOAI group ranked 4th in the "NASA Harvest Field Boundary Detection Challenge" out of 730 participants.<br> Our solution is made public via following repo:<br><a href="https://github.com/geoaigroup/nasa_harvest_boundary_detection_challenge" targe=_blank>https://github.com/geoaigroup/nasa_harvest_boundary_detection_challenge</a>'
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: NASAHarvest.jpeg
        fit: cover
    - title: Sci-Net
      content: 'Our new paper "Sci-Net: scale-invariant model for buildings segmentation from aerial imagery" was just published online:<br><a href="https://link.springer.com/article/10.1007/s11760-023-02520-3" target=_blank>https://link.springer.com/article/10.1007/s11760-023-02520-3</a><br>You can interact with Sci-Net model via:<br><a href="http://geoai.cnrs.edu.lb/urbanmodels/" target=_blank>http://geoai.cnrs.edu.lb/urbanmodels/</a>'
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
        url: #contact
---