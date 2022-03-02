---
title: "PSO-PSParameter Synchronization with Particle Swarm Optimization for Distributed Training of Deep Neural Networks."
authors:
- QingYe
- YuxuanHan
- YananSun
- admin
date: "2020-06-19T00:00:00Z"
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

abstract: "Parameter updating is an important stage in parallelism-based distributed deep learning. Synchronous methods are widely used in distributed training the Deep Neural Networks (DNNs). To reduce the communication and synchronization overhead of synchronous methods, decreasing the synchronization frequency (e.g., every n mini-batches) is a straightforward approach. However, it often suffers from poor convergence. In this paper, we propose a new algorithm of integrating Particle Swarm Optimization (PSO) into the distributed training process of DNNs to automatically compute new parameters. In the proposed algorithm, a computing work is encoded by a particle, the weights of DNNs and the training loss are modeled by the particle attributes. At each synchronization stage, the weights are updated by PSO from the sub weights gathered from all workers, instead of averaging the weights or the gradients. To verify the performance of the proposed algorithm, the experiments are performed on two commonly used image classification benchmarks: MNIST and CIFAR10, and compared with the peer competitors at multiple different synchronization configurations. The experimental results demonstrate the competitiveness of the proposed algorithm."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9207698'
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
