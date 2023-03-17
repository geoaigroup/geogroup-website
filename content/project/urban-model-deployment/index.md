---
title: GEOAI Urban Tool
summary: Web-based tool to extract buildings footprint using AI

draft: false
featured: false
tags:
  - Deep Learning


date: 2023-03-15T09:07:29.350Z
weight: 1
---

GEOAI Urban Tool is a web-based tool that enables you to extract buildings footprint from satellite/aerial imagery powered by AI.
The incentive is to take our research a step forward and make those research results accessible to a larger community of interested users beyond specialist EO scholars. Though it is not common to develop such a tool for a team that is mainly involved with applied research rather than product development. We believe this demo tool would help us target a larger audience and would open up new horizons for the GEOAI group.

Via following <a href="http://geoai.cnrs.edu.lb/urbanmodels/" target="_blank">LINK</a>, you can interact with three CNN-based deep learning models:
1. General Model: trained on a satellite dataset (WHU) with 30-cm resolution using our multi-class instance segmentation technique.
2. Sci-Net Model: trained on a drone dataset with spatial resolution varying from 2-cm to 20-cm using our scale-invariant semantic segmentation technique.
3. Lebanese Model: trained on our Lebanese satellite dataset with 50-cm spatial resolution using our multi-class instance segmentation technique.

Segmentation of buildings using these three models exhibit high pixel-wise metric scores.


