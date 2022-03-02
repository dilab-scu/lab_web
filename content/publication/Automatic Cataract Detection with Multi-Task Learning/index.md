---
title: "Automatic Cataract Detection with Multi-Task Learning."
authors:
- HongjieWu
- admin
- JianWang
date: "2021-06-18T00:00:00Z"
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

abstract: "Cataract is one of the most prevalent diseases among the elderly. As the population ages, the incidence of cataracts is on the rise. Early diagnosis and treatment are essential for cataracts. The routine early diagnosis relies on B-scan eye ultrasound images, developing deep learning-based automatic cataract detection makes great sense. However, ultrasound images are complex and contain irrelevant backgrounds, the lens takes up only a small part. Besides, detection networks commonly use only one label as supervision, which leads to low classification accuracy and poor generalization. This paper focuses on making the most of the information in the images, thus proposing a new paradigm for automatic cataract detection. First, an object detection network is included to locate the eyeball area and eliminate the influence of the background. Next, we construct a dataset with multiple labels for each image. We extract the text descriptions of ultrasound images into labels so that each image is tagged with multiple labels. Then we applied the multi-task learning (MTL) methods to cataract detection. The accuracy of classification is significantly improved compared to data with only one label. Last, we propose two gradient-guided auxiliary learning methods to make the auxiliary tasks improve the performance of the main task (cataract detection). The experimental results show that our proposed methods further improve the classification accuracy."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9533424'
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
