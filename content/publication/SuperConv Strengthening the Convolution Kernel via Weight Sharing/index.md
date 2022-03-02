---
title: "SuperConv Strengthening the Convolution Kernel via Weight Sharing."
authors:
- ChuanLiu
- QingYe
- XiaomingHuang
- admin
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

abstract: "For the current neural network models, in order to improve the accuracy of the models, we need efficient plug-and-play modules. Therefore, many efficient plug-and-play operations are proposed, such as Asymmetric Convolution Block (ACB). However, the introduction of multi-branch convolution kernels in ACB increases the trainable parameters, which is an extra burden to the training of large models. In this work, SuperConv is proposed to reduce the trainable parameters while maintaining the advantages of ACB. SuperConv utilizes the method in single-path NAS to encode the convolution kernels of different sizes in multiple branches into a super-kernel, so that the convolution kernels can share some weights with each other. In addition, we introduce SuperConv into MixConv and propose SuperMixConv (SP-MixConv). To verify the effectiveness of SP-MixConv, ACB, MixConv and SP-MixConv are inserted into the Cifar-quick model and the model with SP-MixConv gets the best accuracy on CIFAR-10 and CIFAR-100. And SuperConv and SP-MixConv will not add extra burden in inference. Simultaneously, SuperConv is very easy to implement, using existing tools such as Pytorch, and is also an interesting attempt for the design of efficient plug-and-play convolution block."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://www.researchgate.net/publication/347056231_SuperConv_Strengthening_the_Convolution_Kernel_via_Weight_Sharing'
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
