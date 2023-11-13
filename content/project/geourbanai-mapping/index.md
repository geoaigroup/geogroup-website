---
title: GeoUrban-AI Mapping
summary: Urban Monitoring through Earth Observation

draft: false
featured: false
tags:
  - Deep Learning


date: 2023-02-13T09:07:29.350Z
---

<div class=article-style itemprop=articleBody>

<b><h2 id=geourban-ai-tool>GeoUrban-AI Tool</h2></b>
<p>GeoUrban-AI powered <a href="http://geoai.cnrs.edu.lb/urbanmodels/" target="_blank">[Tool]</a> allows to autonomously extract buildings' footprints from satellite/aerial imagery. The aim is to make our applied research findings accessible to a larger community. Though it is not common to develop such a web-based tool for a team that is mainly involved with research rather than product development; We believe this demo would help us target a larger audience and would open up new horizons for the GEOAI group.</p>

<img src="./lebanonmap.png">

<b><h2 id=lebanese-buildings-footprints-map>Lebanese Building Footprints map</h2></b>
<p>Developing countries usually lack the proper governance means to generate and regularly update a national rooftop map. Using traditional photogrammetry and surveying methods to produce buildings map at the federal level is costly and time-consuming. Relying on earth observation and deep learning methods, we propose in this project to bridge this gap and propose an automated pipeline to fetch such urban maps automatically. We proposed several new architectures that advance state-of-the-art technology and also provide an application targeted to the Lebanese context where we present the first comprehensive Lebanese Building Footprints map, autonomously generated using deep learning models.

<a href="http://geoai.cnrs.edu.lb/urbanmap/" target="_blank">[Map]</a> encompases  ~800, 000 urban units with an accuracy of about 84%. When you ZOOM IN, the dots on the map refer to the centroids of each building at a specific geographical location <a href="https://geogroup.ai/publication/2022SolarMapLebanon/">[Paper]</a></p>.

<img src="./solar.png">

<b><h2 id=solar-potential>Solar Potential Map for Lebanon</h2></b>
<p>Estimating the solar potential of buildings' rooftops at a large scale is a fundamental step for every country to utilize its solar power efficiently. However, such estimation becomes time-consuming and costly if done through on-site measurements. This project uses deep learning-based multi-class instance segmentation to extract buildings' footprints from satellite images. We propose a photovoltaic panels placement algorithm to estimate the solar potential of every rooftop, which results in Lebanon's first buildings' solar potential map. We report average and total solar potential per district and localize regions corresponding to the highest solar potential yield <a href="https://geogroup.ai/publication/2022SolarMapLebanon/">[Paper]</a>.</p>

<p><img src=./scinet.jpg title="Sci-Net architecture"></p>

<b><h2 id=sci-net>Sci-Net: a Scale Invariant Model for Building Detection from Aerial Images</h2><p></b>
Buildings' segmentation is a fundamental task in the field of earth observation and aerial imagery analysis. Most existing deep learning based algorithms in the literature can be applied to fixed or narrow-ranged spatial resolution imagery. In practical scenarios, users deal with a wide spectrum of images resolution and thus, often need to resample a given aerial image to match the spatial resolution of the dataset used to train the deep learning model. This however, would result in a severe degradation in the quality of the output segmentation masks. To deal with this issue, we propose in this research a Scale-invariant neural network (Sci-Net) that is able to segment buildings present in aerial images at different spatial resolutions. Specifically, we modified the U-Net architecture and fused it with dense Atrous Spatial Pyramid Pooling (ASPP) to extract fine-grained multi-scale representations. We compared the performance of our proposed model against several state-of-the-art models on the Open Cities AI dataset, and showed that Sci-Net provides a steady improvement margin in performance across all resolutions available in the dataset <a href="https://geogroup.ai/publication/2022SciNet/">[Paper]</a>.</p>

<p><img src=./bdabtc.jpg title="Buildings Classification using Very High Resolution Satellite Imagery"></p>

<b><h2 id=bda-btc>Buildings Classification using Very High Resolution Satellite Imagery</h2><p></b>
Buildings classification using satellite images is becoming more important for several applications such as damage assessment, resource allocation, and population estimation. We focus, in this work on buildings type classification (BTC) of residential and non-residential buildings. We propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach. Due to the lack of an appropriate dataset for the residential/non-residential building classification, we introduce a new dataset of high-resolution satellite images. We conducted extensive experiments to select the best hyper-parameters, model architecture, and training paradigm, and we propose a new transfer learning-based approach that outperforms classical methods <a href="https://geogroup.ai/publication/2023ECRS_BDABTC/">[Paper]</a>.</p>


</div>
