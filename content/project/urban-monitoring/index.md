---
title: Urban Monitoring through Earth Observation
summary: The first comprehensive Lebanese Building Footprints autonomously generated using Deep Learning.

draft: false
featured: false
tags:
  - Deep Learning


date: 2021-12-13T09:07:29.350Z

---

Urban Monitoring through Earth Observation is a crucial theme that encompasses several applications. In this project, we tackled buildings’ segmentation, buildings’ type classification and buildings’ damage assessment. We proposed several new architectures that advance state-of-the-art technology and also provide an application targeted to the Lebanese context where we present the first comprehensive Lebanese Building Footprints map, autonomously generated using deep learning models. When you ZOOM IN, the dots on the map refer to the centroids of each building at a specific geographical location. The map can be accessed via the following <a href="http://geoai.cnrs.edu.lb/urbanmap/" target="_blank">LINK</a>.

Buildings' segmentation is a fundamental task in the field of earth observation and aerial imagery analysis. Most existing deep learning based algorithms in the literature can be applied to fixed or narrow-ranged spatial resolution imagery. In practical scenarios, users deal with a wide spectrum of images resolution and thus, often need to resample a given aerial image to match the spatial resolution of the dataset used to train the deep learning model. This however, would result in a severe degradation in the quality of the output segmentation masks. To deal with this issue, we propose in this research a Scale-invariant neural network (Sci-Net) that is able to segment buildings present in aerial images at different spatial resolutions. Specifically, we modified the U-Net architecture and fused it with dense Atrous Spatial Pyramid Pooling (ASPP) to extract fine-grained multi-scale representations. We compared the performance of our proposed model against several state-of-the-art models on the Open Cities AI dataset, and showed that Sci-Net provides a steady improvement margin in performance across all resolutions available in the dataset.

Moreover, buildings classification using satellite images is becoming more important for several applications such as damage assessment, resource allocation, and population estimation. We focus, in this work on buildings type classification (BTC) of residential and non-residential buildings. We propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach. In a nutshell,  in the first stage, buildings’ footprints are extracted using a semantic segmentation model, while in the second stage, the model classifies the cropped images around buildings into 2 classes; residential and non-residential. Due to the lack of an appropriate dataset for the residential/non-residential building classification, we introduce a new dataset of high-resolution satellite images.

Finally, regarding buildings' damage assessment, we propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach, where first, buildings’ footprints are extracted using a semantic segmentation model, followed by classification of the cropped images into damaged or non-damaged building. We conduct extensive experiments to select the best hyper-parameters, model architecture, and training paradigm, and we propose a new transfer learning-based approach that outperforms classical methods. Finally, we validate the proposed approach showing excellent accuracy and F1-score metrics.