---
title: "Heart-Darts: Classification of Heartbeats Using Differentiable Architecture Search."
authors:
- JindiLv
- QingYe
- YannanSun
- JuanZhao
- admin
date: "2021-05-03T00:00:00Z"
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

abstract: "Arrhythmia is a cardiovascular disease that manifests irregular heartbeats. In arrhythmia detection, the electrocardiogram (ECG) signal is an important diagnostic technique. However, manually evaluating ECG signals is a complicated and time-consuming task. With the application of convolutional neural networks (CNNs), the evaluation process has been accelerated and the performance is improved. It is noteworthy that the performance of CNNs heavily depends on their architecture design, which is a complex process grounded on expert experience and trial-and-error. In this paper, we propose a novel approach, Heart-Darts, to efficiently classify the ECG signals by automatically designing the CNN model with the differentiable architecture search (i.e., Darts, a cell-based neural architecture search method). Specifically, we initially search a cell architecture by Darts and then customize a novel CNN model for ECG classification based on the obtained cells. To investigate the efficiency of the proposed method, we evaluate the constructed model on the MIT-BIH arrhythmia database. Additionally, the extensibility of the proposed CNN model is validated on two other new databases. Extensive experimental results demonstrate that the proposed method outperforms several state-of-the-art CNN models in ECG classification in terms of both performance and generalization capability."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://arxiv.org/pdf/2105.00693.pdf'
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
