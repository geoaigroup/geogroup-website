---
publication_types:
  - "1"

authors:
  - abdulkarim_gizzini
  - mustafa_shukor 
  - admin
  
url_pdf: "https://arxiv.org/pdf/2310.01837.pdf"
url_dataset: ""
url_project: "https://geogroup.ai/project/xai/"
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "Extending GradCam-based XAI methods for Remote Sensing Imagery Segmentation"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - xai


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2023-10-04T00:00:00Z"


abstract: "Artificial intelligence (AI) has recently covered many earth observation applications. AI-based data-driven methods perform outstandingly in several remote sensing image processing tasks, such as object detection, classification, and segmentation. However, current AI-based methods do not provide comprehensible physical interpretations of the utilized data, extracted features, and predictions/inference operations. As a result, deep learning models trained using high-resolution satellite imagery lack transparency and explainability and can be merely seen as a black box, which limits their wide-level adoption. Experts need help understanding the complex behavior of AI models and the underlying decision-making process. The explainable artificial intelligence (XAI) field is an emerging field providing means for robust, practical, and trustworthy deployment of AI models. Several XAI techniques have been proposed for image classification tasks, whereas the interpretation of image segmentation remains largely unexplored. This paper offers to bridge this gap by adapting 11 different gradient-based classification algorithms and making them usable for muti-class image segmentation, where we mainly focus on buildings' segmentation from high-resolution satellite images. To benchmark and compare the performance of the proposed approaches, we introduce a new XAI evaluation metric based on Entropy to measure the model uncertainty. Conventional XAI evaluation methods rely mainly on feeding area-of-interest regions from the image back to the pre-trained (utility) model and then calculating the average change in the probability of the target class. Those evaluation metrics lack the needed robustness, and we show that using Entropy to monitor the model uncertainty in segmenting the pixels within the target class is more suitable. We hope this work will pave the way for additional XAI research for image segmentation and applications in the remote sensing discipline."
---
