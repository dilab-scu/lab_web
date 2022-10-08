---
title: "CDD: Multi-view Subspace Clustering via Cross-view Diversity Detection."
authors:
- ShudongHuang
- Tsang Ivor W
- ZenglinXu
- admin
- QuanhuiLiu
date: "2021-10-17T00:00:00Z"
doi: "https://doi.org/10.1145/3474085.3475393"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Association for Computing Machinery"
publication_short: "ACM"

abstract: "The goal of multi-view subspace clustering is to explore a common latent space where the multi-view data points lying on. Myriads of subspace learning algorithms have been investigated to boost the performance of multi-view clustering, but seldom exploiting both the multi-view consistency and multi-view diversity, let alone taking them into consideration simultaneously. To do so, we lodge a novel multi-view subspace clustering via cross-view diversity detection (CDD). CDD is able to exploit these two complementary criteria seamlessly into a holistic design of clustering algorithms. With the consistent part and diverse part being detected, a pure graph can be derived for each view. The consistent pure parts of different views are further fused to a consensus structured graph with exactly k connected components where k is the number of clusters. Thus we can directly obtain the final clustering result without any postprocessing as each connected component precisely corresponds to an individual cluster. We model the above concerns into a unified optimization framework. Our empirical studies validate that the proposed model outperforms several other state-of-the-art methods."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3474085.3475393'
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