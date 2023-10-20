---
publication_types:
  - pub_paper_conference

authors:
  - mohamad_zahweh
  - hasan_nasrallah
  - mustafa_shukor
  - ghaleb_faour
  - admin
  
url_pdf: https://arxiv.org/pdf/2310.01825.pdf
url_dataset: ""
url_project: https://geogroup.ai/project/crop-monitoring/
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "Empirical Study of PEFT techniques for Winter Wheat Segmentation"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - crop-monitoring


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2023-10-04T00:00:00Z"

abstract: "Parameter Efficient Fine Tuning (PEFT) techniques have recently experienced significant growth and have been extensively employed to adapt large vision and language models to various domains, enabling satisfactory model performance with minimal computational needs. However, despite these advancements, more research has yet to delve into potential PEFT applications in real-life scenarios, particularly in the critical domains of remote sensing and crop monitoring. In the realm of crop monitoring, a key challenge persists in addressing the intricacies of cross-region and cross-year crop type recognition. The diversity of climates across different regions and the need for comprehensive, large-scale datasets have posed significant obstacles in accurately identifying crop types across varying geographic locations and changing growing seasons. This study seeks to bridge this gap by comprehensively exploring the feasibility of cross-area and cross-year out-of-distribution generalization using the State-of-the-Art (SOTA) wheat crop monitoring model. This research mainly focuses on adapting the SOTA TSViT model, recently proposed in CVPR 2023, to address winter-wheat field segmentation, a critical task for crop monitoring and food security, especially following the Ukrainian conflict, given the economic importance of wheat as a staple and cash crop in various regions. This adaptation process involves integrating different PEFT techniques, including BigFit, LoRA, Adaptformer, and prompt tuning, each designed to streamline the fine-tuning process and ensure efficient parameter utilization. By employing PEFT techniques, we achieved notable results comparable to those attained through Full Fine-Tuning methods while training only a mere 0.7% parameters of the whole TSViT architecture. More importantly, we accomplished the claimed performance using a limited subset of remotely labeled data. The in-house labeled dataset, referred to as the Lebanese Wheat dataset, comprises high-quality annotated polygons for wheat and non-wheat classes for the study area in Bekaa, Lebanon, with a total surface of 170 km², over five consecutive years from 2016 until 2020. Using a time series of multi-spectral Sentinel-2 images, our model achieved an 84% F1-score when evaluated on the test set, shedding light on the capacity of PEFT to drive accurate and efficient crop monitoring, tailored mainly for developing countries characterized by limited data availability. We intend to publicly release the Lebanese winter wheat dataset, code repository, and model weights."

---
