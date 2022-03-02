---
title: "CR-GAN: Automatic craniofacial reconstruction for personal identification."
authors:
- YuanLi
- JianWang
- WeiboLiang
- HuiXue
- ZhenanHe
- admin
- LinZhang
date: "2021-10-26T00:00:00Z"
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

abstract: "Craniofacial reconstruction is applied to identify human remains in the absence of determination data (e.g., fingerprinting, dental records, radiological materials, or DNA), by predicting the likeness of the unidentified remains based on the internal relationship between the skull and face. Conventional 3D methods are usually based on statistical models with poor capacity, which limit the description of such complex relationship. Moreover, the required high-quality data are difficult to collect. In this study, we present a novel craniofacial reconstruction paradigm that synthesize craniofacial images from 2D computed tomography scan of skull data. The key idea is to recast craniofacial reconstruction as an image translation task, with the goal of generating corresponding craniofacial images from 2D skull images. To this end, we design an automatic skull-to-face transformation system based on deep generative adversarial nets. The system was trained on 4551 paired skull-face images obtained from 1780 CT head scans of the Han Chinese population. To the best of our knowledge, this is the only database of this magnitude in the literature. Finally, to accurately evaluate the performance of the model, a face recognition task employing five existing deep learning algorithms, —FaceNet, —SphereFace, —CosFace, —ArcFace, and —MagFace, was tested on 102 reconstruction cases in a face pool composed of 1744 CT-scan face images. The experimental results demonstrate that the proposed method can be used as an effective forensic tool."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0031320321005768/pdfft?md5=d495544a9fb2d4498b2c2ceede57daf0&pid=1-s2.0-S0031320321005768-main.pdf'
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
