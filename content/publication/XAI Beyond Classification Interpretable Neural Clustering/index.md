---
title: "XAI Beyond Classification: Interpretable Neural Clustering."
authors:
- Xi Peng
- YunfanLi
- Ivor W. Tsang
- HongyuanZhu
- Joey TianyiZhou
- admin
date: "2022-02-22T00:00:00Z"
doi: "10.48550/arXiv.1808.07292"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Machine Learning Research "
publication_short: ""

abstract: "In this paper, we study two challenging problems in explainable AI (XAI) and data clustering. The first is how to directly design a neural network with inherent interpretability, rather than giving
post-hoc explanations of a black-box model. The second is implementing discrete k-means with a differentiable neural network that embraces the advantages of parallel computing, online clustering, and clustering-favorable representation learning. To address these two challenges, we design
a novel neural network, which is a differentiable reformulation of the vanilla k-means, called inTerpretable nEuraL cLustering (TELL). Our contributions are threefold. First, to the best of our knowledge, most existing XAI works focus on supervised learning paradigms. This work is one
of the few XAI studies on unsupervised learning, in particular, data clustering. Second, TELL is an interpretable, or the so-called intrinsically explainable and transparent model. In contrast, most existing XAI studies resort to various means for understanding a black-box model with post-hoc
explanations. Third, from the view of data clustering, TELL possesses many properties highly desired by k-means, including but not limited to online clustering, plug-and-play module, parallel
computing, and provable convergence. Extensive experiments show that our method achieves superior performance comparing with 14 clustering approaches on three challenging data sets. The source code could be accessed at www.pengxi.me."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9206919'
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