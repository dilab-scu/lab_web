---
title: "Cataract detection based on ocular B-ultrasound images by collaborative monitoring deep learning."
authors:
- YongWang
- ChenweiTang
- JianWang
- YongshegSang
- admin
date: "2021-11-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In this paper, we collect an ocular B-ultrasound image dataset and propose a Collaborative Monitoring Deep Learning (CMDL) method to detect cataract. In the ocular B-ultrasound images, there are often strong echoes near the posterior capsule and lens, and the fine-grained ocular B-ultrasound images are often accompanied by the characteristics of weak penetrating power, low contrast, narrow imaging range, and high noise. Thus, in the proposed CMDL method, we introduce an object detection network based on YOLO-v3 to detect the focus areas we need, so as to reduce the interference of noise and improve the cataract detection accuracy of our method. Considering that the B-ultrasound image dataset we collected is small-scale, we also design three feature extraction modules to avoid over-fitting of the deep neural networks. Among them, there are a depth features extraction module based on DenseNet-161, a shape features extractor based on Fourier descriptor, and a texture features extraction module based on gray-level co-occurrence matrix. Moreover, we also introduce the collaborative learning module to improve the generalization of the proposed model. Specifically, we first fuse the depth, shape, and texture features of the eyeball and lens, respectively. Then, the fused features of the eyeball and lens are concatenated as the input of collaborative network. Finally, the introduced classification loss with the aid of collaborative loss, which distinguishes whether the eyeball and lens belong to the same category, improves the classification accuracy in cataract detection. Experimental results on our collected dataset demonstrate the effectiveness of the proposed CMDL method."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://pdf.sciencedirectassets.com/271505/1-s2.0-S0950705121X00184/1-s2.0-S0950705121007048/main.pdf'
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
