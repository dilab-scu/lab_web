---
title: "Spark Rough Hypercuboid Approach for Scalable Feature Selection."
authors:
- ChuanLuo
- SizhaoWang
- TianruiLi
- HongmeiChen
- YiZhang
- admin
date: "2021-09-14T00:00:00Z"
doi: "https://doi.org/10.1109/TKDE.2021.3112520"

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

abstract: "Feature selection refers to choose an optimal non-redundant feature subset with minimal degradation of learning performance and maximal avoidance of data overfitting. The appearance of large data explosion leads to the sequential execution of algorithms are extremely time-consuming, which necessitates the scalable parallelization of algorithms by efficiently exploiting the distributed computational capabilities. In this paper, we present parallel feature selection algorithms underpinned by a rough hypercuboid approach in order to scale for the growing data volumes. Metrics in terms of rough hypercuboid are highly suitable to parallel distributed processing, and fits well with the Apache Spark cluster computing paradigm. Two data parallelism strategies, namely, vertical partitioning and horizontal partitioning, are implemented respectively to decompose the data into concurrent iterative computing streams. Experimental results on representative datasets show that our algorithms significantly faster than its original sequential counterpart while guaranteeing the quality of the results. Furthermore, the proposed algorithms are perfectly capable of exploiting the distributed-memory clusters to accomplish the computation task that fails on a single node due to the memory constraints. Parallel scalability and extensibility analysis have confirmed that our parallelization extends well to process massive amount of data and can scales well with the increase of computational nodes."


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