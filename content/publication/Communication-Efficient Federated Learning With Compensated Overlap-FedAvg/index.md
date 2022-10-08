---
title: "Communication-Efficient Federated Learning With Compensated Overlap-FedAvg."
authors:
- Yuhao Zhou
- Qing Ye
- Jiancheng Lv
date: "2021-06-17T00:00:00Z"
doi: "10.1109/TPDS.2021.3090331"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Parallel and Distributed Systems "
publication_short: ""

abstract: "While petabytes of data are generated each day by a number of independent computing devices, only a few of them can be finally collected and used for deep learning (DL) due to the apprehension of data security and privacy leakage, thus seriously retarding the extension of DL. In such a circumstance, federated learning (FL) was proposed to perform model training by multiple clients' combined data without the dataset sharing within the cluster. Nevertheless, federated learning with periodic model averaging (FedAvg) introduced massive communication overhead as the synchronized data in each iteration is about the same size as the model, and thereby leading to a low communication efficiency. Consequently, variant proposals focusing on the communication rounds reduction and data compression were proposed to decrease the communication overhead of FL. In this article, we propose Overlap-FedAvg, an innovative framework that loosed the chain-like constraint of federated learning and paralleled the model training phase with the model communication phase (i.e., uploading local models and downloading the global model), so that the latter phase could be totally covered by the former phase. Compared to vanilla FedAvg, Overlap-FedAvg was further developed with a hierarchical computing strategy, a data compensation mechanism, and a nesterov accelerated gradients (NAG) algorithm. In Particular, Overlap-FedAvg is orthogonal to many other compression methods so that they could be applied together to maximize the utilization of the cluster. Besides, the theoretical analysis is provided to prove the convergence of the proposed framework. Extensive experiments conducting on both image classification and natural language processing tasks with multiple models and datasets also demonstrate that the proposed framework substantially reduced the communication overhead and boosted the federated learning process."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/document/9459540'
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