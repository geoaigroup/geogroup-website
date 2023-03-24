---
title: GeoUrban-AI Tool
summary: Ai-powered web-based tool to extract buildings' footprint

draft: false
featured: false
tags:
  - Deep Learning


date: 2023-03-15T09:07:29.350Z
weight: 1
---

GeoUrban-AI powered Tool tool allows to autonomously extract buildings' footprints from satellite/aerial imagery.
The aim is to make our applied research findings accessible to a larger community. Though it is not common to develop such a web-based tool for a team that is mainly involved with research rather than product development; We believe this demo would help us target a larger audience and would open up new horizons for the GEOAI group.

Via following <a href="http://geoai.cnrs.edu.lb/urbanmodels/" target="_blank">LINK</a>, you can interact with three CNN-based deep learning models:
1. General Model: trained on a satellite dataset (WHU) with 30-cm resolution using our multi-class instance segmentation technique.
2. Sci-Net Model: trained on a drone dataset with spatial resolution varying from 2-cm to 20-cm using our scale-invariant semantic segmentation technique.
3. Lebanese Model: trained on our Lebanese satellite dataset with 50-cm spatial resolution using our multi-class instance segmentation technique.

Segmentation of buildings using these three models exhibit high pixel-wise metric scores.


