---
title: "Attention-Based Multi-Model Ensemble for Automatic Cataract Detection in B-Scan Eye Ultrasound Images."
authors:
- XiaofeiZhang
- admin
- HengZheng
- YongshengSang
date: "2020-07-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Accurate detection of early-stage cataract is essential for preventing blindness, but clinical cataract diagnosis requires the professional knowledge of experienced ophthalmologists, which may present difficulties for cataract patients in poverty-stricken areas. Deep learning method has been successful in many image classification tasks, but there are still huge challenges in the field of automatic cataract detection due to two characteristics of cataract and its B-scan eye ultrasound images. First, cataract is a disease that occurs in the lens of the eyeball, but the eyeball occupies only a small part of the eye B-ultrasound image. Second, lens lesions in eye B-ultrasound images are diverse, resulting in small difference and high similarity between positive and negative samples. In this paper, we propose a multi-model ensemble method based on residual attention for cataract classification. The proposed model consists of an object detection network, three pre-trained classification networks: DenseNet-161, ResNet-152 and ResNet-101, and a model ensemble module. Each classification network incorporates a residual attention module. Experimental results on the benchmark B-scan eye ultrasound dataset show that our method can adaptively focus on the discriminative areas of cataract in the eyeball and achieves an accuracy of 97.5%, which is markedly superior to the five baseline methods."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9207696'
#url_code: '#'
#url_dataset: '#'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
