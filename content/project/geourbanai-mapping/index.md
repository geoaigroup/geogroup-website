---
title: GeoUrban-AI Mapping
summary: Urban Monitoring through Earth Observation

draft: false
featured: false
tags:
  - Deep Learning


date: 2021-12-13T09:07:29.350Z

---

<div class=article-style itemprop=articleBody>

<strong><h2 id=geourban-ai-tool>GeoUrban-AI Tool</h2></strong>
<p>GeoUrban-AI powered Tool allows to autonomously extract buildings' footprints from satellite/aerial imagery. The aim is to make our applied research findings accessible to a larger community. Though it is not common to develop such a web-based tool for a team that is mainly involved with research rather than product development; We believe this demo would help us target a larger audience and would open up new horizons for the GEOAI group. <a href="http://geoai.cnrs.edu.lb/urbanmodels/" target="_blank">[Tool]</a></p>

<p><img src=./lebanonmap.png alt title="Lebanese Building Footprints map"></p>
<strong><h2 id=lebanese-buildings-footprints-map>Lebanese Building Footprints map</h2></strong>
<p>Urban Monitoring through Earth Observation is a crucial theme that encompasses several applications. In this project, we tackled buildings’ segmentation, buildings’ type classification and buildings’ damage assessment. We proposed several new architectures that advance state-of-the-art technology and also provide an application targeted to the Lebanese context where we present the first comprehensive Lebanese Building Footprints map, autonomously generated using deep learning models. When you ZOOM IN, the dots on the map refer to the centroids of each building at a specific geographical location. <a href="http://geoai.cnrs.edu.lb/urbanmap/" target="_blank">[Map]</a><a href="https://geogroup.ai/publication/solar2022/">[Paper]</a></p>

<p><img src=./solar.png alt title="Solar Potential Map for Lebanon"></p>
<strong><h2 id=solar-potential>Solar Potential Map for Lebanon</h2></strong>
<p>Estimating the solar potential of buildings' rooftops at a large scale is a fundamental step for every country to utilize its solar power efficiently. However, such estimation becomes time-consuming and costly if done through on-site measurements. This project uses deep learning-based multi-class instance segmentation to extract buildings' footprints from satellite images. We propose a photovoltaic panels placement algorithm to estimate the solar potential of every rooftop, which results in Lebanon's first buildings' solar potential map. We report average and total solar potential per district and localize regions corresponding to the highest solar potential yield. <a href="http://geoai.cnrs.edu.lb/urbanmap/" target="_blank">[Map]</a><a href="https://geogroup.ai/publication/solar2022/">[Paper]</a></p>

<p><img src=./scinet.jpg alt title="Sci-Net architecture"></p>
<strong><h2 id=sci-net>Sci-Net: a Scale Invariant Model for Building Detection from Aerial Images</h2><p></strong>
Buildings' segmentation is a fundamental task in the field of earth observation and aerial imagery analysis. Most existing deep learning based algorithms in the literature can be applied to fixed or narrow-ranged spatial resolution imagery. In practical scenarios, users deal with a wide spectrum of images resolution and thus, often need to resample a given aerial image to match the spatial resolution of the dataset used to train the deep learning model. This however, would result in a severe degradation in the quality of the output segmentation masks. To deal with this issue, we propose in this research a Scale-invariant neural network (Sci-Net) that is able to segment buildings present in aerial images at different spatial resolutions. Specifically, we modified the U-Net architecture and fused it with dense Atrous Spatial Pyramid Pooling (ASPP) to extract fine-grained multi-scale representations. We compared the performance of our proposed model against several state-of-the-art models on the Open Cities AI dataset, and showed that Sci-Net provides a steady improvement margin in performance across all resolutions available in the dataset. <a href="https://geogroup.ai/publication/scinet2022/">[Paper]</a></p>

<p><img src=./bdabtc.jpg alt title="Buildings Classification using Very High Resolution Satellite Imagery"></p>
<strong><h2 id=bda-btc>Buildings Classification using Very High Resolution Satellite Imagery</h2><p></strong>
Buildings classification using satellite images is becoming more important for several applications such as damage assessment, resource allocation, and population estimation. We focus, in this work on buildings type classification (BTC) of residential and non-residential buildings. We propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach. In a nutshell,  in the first stage, buildings’ footprints are extracted using a semantic segmentation model, while in the second stage, the model classifies the cropped images around buildings into 2 classes; residential and non-residential. Due to the lack of an appropriate dataset for the residential/non-residential building classification, we introduce a new dataset of high-resolution satellite images.

Regarding buildings' damage assessment, we propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach, where first, buildings’ footprints are extracted using a semantic segmentation model, followed by classification of the cropped images into damaged or non-damaged building. We conduct extensive experiments to select the best hyper-parameters, model architecture, and training paradigm, and we propose a new transfer learning-based approach that outperforms classical methods. Finally, we validate the proposed approach showing excellent accuracy and F1-score metrics. <a href="https://geogroup.ai/publication/bdabtc2021/">[Paper]</a></p>


</div>