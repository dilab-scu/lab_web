---
title: "A Distributed Framework for EA-Based NAS."
authors:
- Qing Ye
- Yanan Sun
- Jixin Zhang
- Jiancheng Lv
date: "2020-12-23T00:00:00Z"
doi: "10.1109/TPDS.2020.3046774"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: " IEEE Transactions on Parallel and Distributed Systems "
publication_short: ""

abstract: "Evolutionary Algorithms (EA) are widely applied in Neural Architecture Search (NAS) and have achieved appealing results. Different EA-based NAS algorithms may utilize different encoding schemes for network representation, while they have the same workflow. Specifically, the first step is the initialization of the population with different encoding schemes, and the second step is the evaluation of the individuals by the fitness function. Then, the EA-based NAS algorithm executes evolution operations, e.g., selection, mutation, and crossover, to eliminate weak individuals and generate more competitive ones. Lastly, evolution continues until the max generation and the best neural architectures will be chosen. Because each individual needs complete training and validation on the target dataset, the EA-based NAS always consumes significant computation and time inevitably, which results in the bottleneck of this approach. To ameliorate this issue, this article proposes a distributed framework to boost the computation of the EA-based NAS algorithm. This framework is a server/worker model where the server distributes individuals requested by the computing nodes and collects the validated individuals and hosts the evolution operations. Meanwhile, the most time-consuming phase (i.e., individual evaluation) of the EA-based NAS is allocated to the computing nodes, which send requests asynchronously to the server and evaluate the fitness values of the individuals. Additionally, a new packet structure of the message delivered in the cluster is designed to encapsulate various network representations and support different EA-based NAS algorithms. We design an EA-based NAS algorithm as a case to investigate the efficiency of the proposed framework. Extensive experiments are performed on an illustrative cluster with different scales, and the results reveal that the framework can achieve a nearly linear reduction of the search time with the increase of the computational nodes.Furthermore, the length of the exchanged messages among the cluster is tiny, which benefits the framework expansion.
"

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/document/9305984'
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