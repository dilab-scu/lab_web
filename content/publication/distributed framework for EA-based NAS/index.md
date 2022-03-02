---
title: "A distributed framework for EA-based NAS."
authors:
- QingYe
- YananSun
- JixinZhang
- admin
date: "2020-12-23T00:00:00Z"
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

abstract: Evolutionary Algorithms(EA) are widely applied in Neural Architecture Search(NAS) and have achieved appealing results. Different EA-based NAS algorithms may utilize different encoding schemes for network representation, while they have the same workflow (i.e., the initialization of the population, individual evaluation, and evolution). Because each individual needs complete training and validation on the target dataset, the EA-based NAS always consumes significant computation and time inevitably, which results in the bottleneck of this approach. To ameliorate this issue, this paper proposes a distributed framework to boost the computing of the EA-based NAS. This framework is a server/worker model where the server distributes individuals, collects the validated individuals and hosts the evolution operations. Meanwhile, the most time-consuming phase (i.e., individual evaluation) is allocated to the computational workers. Additionally, a new packet structure of the message delivered in the cluster is designed to encapsulate various network representation of different EA-based NAS algorithms. We design an EA-based NAS algorithm as a sample to investigate the effectiveness of the proposed framework. Extensive experiments are performed on an illustrative cluster with different scales, and the results reveal that the framework can achieve a nearly linear reduction of the training time with the increase of the computational workers.

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
