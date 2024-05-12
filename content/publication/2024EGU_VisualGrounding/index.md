---
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

authors:
  - admin
  - hasan_moughnieh
  - mohamad_zahweh
  - hasan_nasrallah
  - mustafa_shukor
  - Cristiano Nattero
  - Paolo Campanella
  
url_pdf: ""
url_dataset: ""
url_project: "https://geogroup.ai/project/geourbanai-mapping/"
url_source: ""
url_video: ""
url_slides: ""
url_poster: "FinalPoster_EGU2024.pdf"
url_code: ""
slides: null

title: "Efficient adaptation of Foundation Models for Visual Grounding Remote Sensing"
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
doi: "10.5194/egusphere-egu24-10914"
date: "2024-04-18T00:00:00Z"

abstract: "Foundation models have demonstrated impressive proficiency across multiple domains, including language, vision, and multi-modal applications, establishing new standards for efficiency and adaptability. In the context of localization-based foundational models, the core strength of such models is their ability to precisely recognize and locate objects across a diverse set of objects in wide-area scenes. This precision is particularly vital in the Remote Sensing (RS) field. The multimodality aspect of these models becomes pivotal in RS, as they can process and interpret complex data, allowing for more comprehensive aerial and satellite image analysis.

Multimodality has emerged as a crucial and dynamic area in recent AI developments, finding diverse applications such as image captioning and visual question answering. More related to traditional visual tasks, Visual Grounding (VG) stands out, involving the localization of objects based on textual descriptions. Unlike conventional approaches that train models on predefined and fixed lists of objects, VG allows a model to locate any entity in an image based on diverse textual descriptions, enabling open-vocabulary predictions. Despite notable efforts in developing powerful VG models to solve general benchmarks, there is a need for more exploration into transferring these models to the remote sensing context.

This paper addresses this gap by delving into the task of visual grounding for remote sensing. Our initial exploration reveals that utilizing general pretrained foundational models for RS yields suboptimal performance. After recognizing these limitations, our work systematically investigates various parameter-efficient tuning techniques to fine-tune these models for RS visual grounding applications. The insights and methodologies presented in this paper provide valuable guidance for researchers seeking to adapt pretrained models to the RS domain efficiently. This adaptation marks a substantial advancement in the field, offering a significant stride toward enhancing the applicability of visual grounding in remote sensing scenarios."

---
