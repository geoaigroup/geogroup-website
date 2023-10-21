---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

authors:
  - ali_mayladan
  - hasan_nasrallah
  - hasan_moughnieh
  - mustafa_shukor
  - admin
  
url_pdf: https://arxiv.org/pdf/2310.01845.pdf
url_dataset: ""
url_project: "https://geogroup.ai/project/geourbanai-mapping/"
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "Zero-Shot Refinement of Buildings' Segmentation Models using SAM"
#publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*"

# Show publication and sharing statistics? (requires valid doi)
add_badge: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - geourbanai-mapping


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption:
  focal_point: ""
  preview_only: false
  
  
featured: false
#doi: "10.1109/JSTARS.2022.3181446"
date: "2023-10-04T00:00:00Z"

abstract: "Foundation models have demonstrated unparalleled performance across diverse tasks involving vision, language, and multimodal domains. Notably, visual foundation models have surpassed the capabilities of prior task-specific models in various dense prediction tasks. Yet, these models still target general benchmarks and are evaluated on curated datasets. The practical adaptation of such models to domain-specific tasks remains an area that has received relatively limited attention. The domain of remote sensing imagery holds significant importance due to its critical real-world applications, such as instance segmentation of buildings, which enables precise identification and analysis of buildings' footprints for various applications, including urban planning and infrastructure development. While Convolutional Neural Networks (CNNs) have demonstrated remarkable capabilities in buildings' rooftop instance segmentation task and have led to the development of cutting-edge models in this domain, they do have certain limitations. One prominent constraint is the limited generalization, where deploying a highly accurate CNN-based buildings footprint segmentation model on unseen data may lead to reduced performance. One may resort to fine-tuning or retraining to enhance the model's performance. For this aim, we present a novel approach to adapt foundation models to address existing models' generalization dropback. Among several models, our focus centers on the Segment Anything Model (SAM), a potent foundation model renowned for its prowess in class-agnostic image segmentation capabilities. We start by identifying the limitations of SAM, revealing its suboptimal performance when applied to remote sensing imagery. Moreover, SAM does not offer recognition abilities and thus fails to classify and tag localized objects. To overcome this, we propose to adapt SAM via prompt engineering. Concretely, our investigation delves into 14 distinct single and composite prompting strategies, encompassing a novel approach that enhances SAM performance by integrating a pre-trained CNN as a prompt generator. To the best of our knowledge, this is the first attempt to augment SAM with a CNN-based prompt generator that offers recognition capabilities. Via a thorough quantitative and qualitative analysis, we evaluate each scenario using three remote sensing datasets: WHU Building Dataset, Massachusetts Buildings Dataset, and AICrowd Mapping Challenge. Our results highlight a substantial enhancement in SAM's buildings segmentation accuracy. Specifically, for out-of-distribution performance on the WHU dataset, we observed a 5.47% and 4.81% improvement in both IoU and F1-score, respectively. We also witnessed 2.72% and 1.58% enhancement in terms of True-Positive-IoU and True-Positive-F1-score, respectively, for in-distribution performance on the WHU dataset."

---
