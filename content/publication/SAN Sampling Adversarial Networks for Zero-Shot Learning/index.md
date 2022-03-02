---
title: "SAN Sampling Adversarial Networks for Zero-Shot Learning."
authors:
- ChenweiTang
- YangzhuKuang
- admin
- JingluHu
date: "2020-11-07T00:00:00Z"
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

abstract: "In this paper, we propose a Sampling Adversarial Networks (SAN) framework to improve Zero-Shot Learning (ZSL) by mitigating the hubness and semantic gap problem. The SAN framework incorporates a sampling model and a discriminating model, and corresponds them to the minimax two-player game. Specifically, given the semantic embedding, the sampling model samples the visual features from the training set to approach the discriminator’s decision boundary. Then, the discriminator distinguishes the matching visual-semantic pairs from the sampled data. On the one hand, by the measurement of the matching degree of visual-semantic pairs and the adversarial training way, the visual-semantic embedding built by the proposed SAN decreases the intra-class distance and increases the inter-class separation. Then, the reduction of universal neighbours in the visual-semantic embedding subspace alleviates the hubness problem. On the other, the sampled rather than directly generated visual features maintain the same manifold as the real data, mitigating the semantic gap problem. Experiments show that the sampler and discriminator of the SAN framework outperform state-of-the-art methods both in conventional and generalized ZSL settings."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://github.com/TCvivi/Sampling-Adversarial-Networks-for-Zero-Shot-Learning'
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
