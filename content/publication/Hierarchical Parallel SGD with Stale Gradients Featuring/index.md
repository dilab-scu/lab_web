---
title: "Hierarchical Parallel SGD with Stale Gradients Featuring."
authors:
- YuhaoZhou
- QingYe
- HailunZhang
- admin
date: "2020-09-06T00:00:00Z"
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

abstract: "While distributed training significantly speeds up the training process of the deep neural network (DNN), the utilization of the cluster is relatively low due to the time-consuming data synchronizing between workers. To alleviate this problem, a novel Hierarchical Parallel SGD (HPSGD) strategy is proposed based on the observation that the data synchronization phase can be paralleled with the local training phase (i.e., Feed-forward and back-propagation). Furthermore, an improved model updating method is unitized to remedy the introduced stale gradients problem, which commits updates to the replica (i.e., a temporary model that has the same parameters as the global model) and then merges the average changes to the global model. Extensive experiments are conducted to demonstrate that the proposed HPSGD approach substantially boosts the distributed DNN training, reduces the disturbance of the stale gradients and achieves better accuracy in given fixed wall-time."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://arxiv.org/pdf/2009.02701.pdf'
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
