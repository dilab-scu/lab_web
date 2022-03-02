---
title: "An Improved Dual-Channel Network to Eliminate Catastrophic Forgetting."
authors:
- DongboLiu,
- ZhenanHe,
- DongdongChen,
- admin
date: "2020-06-16T00:00:00Z"
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

abstract: "Catastrophic forgetting is a chronic problem during the online training process of deep neural networks. That is, once a new data set is used to train an existing neural network, the network will lose the ability to recognize the original data set. In literature, online contrastive divergence (CD) with generative replay (GR) exploits the generative capacity of the neural network to facilitate online training. It greatly alleviates catastrophic forgetting but cannot totally eliminate it. To overcome this shortcoming and further solve the challenging issue, in this article, we propose a novel approach named asynchronous dual-channel online restricted Boltzmann machine, where online CD with dual-channel GR plays an important role in further eliminating catastrophic forgetting. The asynchronous gradient estimation, by which the Markov chain sampling and the network calculation are conducted asynchronously on separate computing nodes, is designed to speed up training. The experimental results show that the proposed method outperforms several algorithms in increasing training speed and minimizing catastrophic forgetting. Besides, online learning with dual-channel can be effectively extended to other online learning neural networks with GR and has achieved excellent results in our verification experiments."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9118953'
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
