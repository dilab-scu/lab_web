---
title: "Arbitrary Chinese Font Generation from a Single Reference."
authors:
- ZhichenLai
- ChenweiTang
- admin
date: "2020-07-19T00:00:00Z"
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

abstract: "Generating a new Chinese font from a multitude of references is an easy task, while it is quite difficult to generate it from a few references. In this paper, we investigate the problem of arbitrary Chinese font generation from a single reference and propose a deep learning based model, named One-reference Chinese Font Generation Network (OCFGNet), to automatically generate any arbitrary Chinese font from a single reference. Based on the disentangled representation learning, we separate the representations of stylized Chinese characters into style and content representations. Then we design a neural network consisting of the style encoder, the content encoder and the joint decoder for the proposed model. The style encoder extracts the style features of style references and maps them onto a continuous Variational Auto-Encoder (VAE) latent variable space while the content encoder extracts the content features of content references and maps them to the content representations. Finally, the joint decoder concatenates both representations in layer-wise to generate the character which has the style of style reference and the content of content reference. In addition, based on Generative Adversarial Network (GAN) structure, we adopt a patch-level discriminator to distinguish whether the received character is real or fake. Besides the adversarial loss, we not only adopt L1-regularized per-pix loss, but also combine a novel loss term Structural SIMilarity (SSIM) together to further drive our model to generate clear and satisfactory results. The experimental results demonstrate that the proposed model can not only extract style and content features well, but also have good performance in the generation of Chinese fonts from a single reference."

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
