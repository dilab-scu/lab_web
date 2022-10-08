---
title: "Measuring Diversity in Graph Learning: A Unified Framework for Structured Multi-view Clustering."
authors:
- ShudongHuang
- IvorTsang
- ZenglinXu
- admin
date: "2021-03-24T00:00:00Z"
doi: "https://doi.org/10.1109/TKDE.2021.3068461"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering"
publication_short: ""

abstract: "Graph Learning has emerged as a promising technique for multi-view clustering due to its efficiency of learning a unified graph from multiple views. Previous multi-view graph learning methods mainly try to exploit the multi-view consistency to boost learning performance. However, these methods ignore the prevalent multi-view diversity which may be induced by noise, corruptions, or even view-specific attributes. In this paper, we propose to simultaneously and explicitly leverage the multi-view consistency and the multi-view diversity in a unified framework. The consistent parts are further fused to our target graph with a clear clustering structure, on which the cluster label to each instance can be directly allocated without any postprocessing such as k-means in classical spectral clustering. In addition, our model can automatically assign suitable weight for each view based on its clustering capacity. By leveraging the subtasks of measuring the diversity of graphs, integrating the consistent parts with automatically learned weights, allocating cluster label to each instance in a joint framework, each subtask can be alternately boosted by utilizing the results of the others towards an overall optimal solution. Extensive experimental results on several benchmark multi-view datasets demonstrate the effectiveness of our model in comparison to several state-of-the-art algorithms."

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