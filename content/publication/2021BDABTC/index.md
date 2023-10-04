---
publication_types:
  - "3"

authors:
  - mohamad_dimassi
  - abed_samhat
  - mohamad_zaraket
  - jamal_haydar
  - mustafa_shukor
  - admin

url_pdf: https://arxiv.org/pdf/2111.14650
url_dataset: "https://storage.googleapis.com/bbtc/bbtc_dataset.tar.gz"
url_project: "https://geogroup.ai/project/geourbanai-mapping/"
url_source: ""
url_video: ""
url_slides: ""
url_poster: ""
url_code: ""
slides: null

title: "Buildings Classification using Very High Resolution Satellite Imagery"

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
#doi: ""
#date: 2021-11-29T00:00:00Z
date: "2021-11-18T00:00:00Z"

abstract: "Buildings classification using satellite images is becoming more important for several applications such as damage assessment, resource allocation, and population estimation. We focus, in this work, on buildings damage assessment (BDA) and buildings type classification (BTC) of residential and non-residential buildings. We propose to rely solely on RGB satellite images and follow a 2-stage deep learning-based approach, where first, buildings' footprints are extracted using a semantic segmentation model, followed by classification of the cropped images. Due to the lack of an appropriate dataset for the residential/non-residential building classification, we introduce a new dataset of high-resolution satellite images. We conduct extensive experiments to select the best hyper-parameters, model architecture, and training paradigm, and we propose a new transfer learning-based approach that outperforms classical methods. Finally, we validate the proposed approach on two applications showing excellent accuracy and F1-score metrics."

---

Beirut Buildings Type Classification (BBTC) dataset is a collection of buildings satellite images from Beirut City where each building is manually annotated as either residential or not. BBTC dataset can be accessed through this <a href="https://storage.googleapis.com/bbtc/bbtc_dataset.tar.gz" target="_blank">GCP bucket</a> where the "Requester Pays" feature is enabled, and thus the requester needs to include a billing project in their requests and will be charged by GCP for their access to the dataset. For more details on how to access a "Requester Pays" bucket object, you can refer to this <a href="https://cloud.google.com/storage/docs/using-requester-pays#rest-access-requester-pays" target="_blank"> documentation.</a>
