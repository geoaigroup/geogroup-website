---
title: Silo Bins
date: 2022-07-10T04:21:25.646Z
summary: Silo Bins detection from Aerial Images
draft: false
featured: false
tags:
- Deep Learning

image:
  filename: featured.png
---
The presence of silo bins can be a good indicator of the existence of a near farm. Such information about the locations of silo bins is often required by decision support systems. In this project, we detect the presence of silos for any given Area Of Interest (AOI) from satellite imagery using using deep learning model. The model takes two inputs: (1) a satellite image and (2) an AOI mask that designates the region in the image under consideration. The satellite image is processed by the main backbone network, while an additional attention network provides spatial information about the pixels to be included in the classification process. The porposed framework was applied on ~8MM AOI accross different states in USA and the resultant classification accuracy was satisfactory.
