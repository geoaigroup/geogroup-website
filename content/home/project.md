---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title:
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Deep Learning
    tag: Deep Learning
  - name: Other
    tag: Other

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: masonry 

  # For Showcase view, flip alternate rows?
  flip_alt_rows: true
---
{{% callout note %}}
GEOspatial Artificial Intelligence (GEOAI) is a research group located at the <a href="http://rsensing.cnrs.edu.lb" target="_blank">National Center for Remote Sensing </a> - <a href="http://www.cnrs.edu.lb" target="_blank">CNRS</a>, Lebanon. Our research is focused on AI-assisted mapping spanning various applications, including urban analytics, transportation, waterbodies monitoring and crop-yield estimation. We develop tools to automate the process of urban features extraction and crowd-source data collection. Evidence gained from our models allows for a robust humanitarian response and provides policymakers/key-stakeholders with insights to design tailored regulations and safety countermeasures for urban social good.<br> GEOAI group provides a unique opportunity for geospatial training in a professional research environment in Lebanon. We have hosted more than 40 students at both undergraduate and graduate levels since 2016.</strong>
{{% /callout %}}