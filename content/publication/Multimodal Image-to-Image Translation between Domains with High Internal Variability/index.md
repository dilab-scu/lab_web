---
title: "Multimodal Image-to-Image Translation between Domains with High Internal Variability."
authors:
- JianWang
- admin
- XueYang
- ChenweiTang
- XiPeng
date: "2020-06-12T00:00:00Z"
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

abstract: "Multimodal image-to-image translation based on generative adversarial networks (GANs) shows suboptimal performance in the visual domains with high internal variability, e.g., translation from multiple breeds of cats to multiple breeds of dogs. To alleviate this problem, we recast the training procedure as modeling distinct distributions which are observed sequentially, for example, when different classes are encountered over time. As a result, the discriminator may forget about the previous target distributions, known as catastrophic forgetting, leading to non-/slow convergence. Through experimental observation, we found that the discriminator does not always forget the previously learned distributions during training. Therefore, we propose a novel generator regulating GAN (GR-GAN). The proposed method encourages the discriminator to teach the generator more effectively when it remembers more of the previously learned distributions, while discouraging the discriminator to guide the generator when catastrophic forgetting happens on the discriminator. Both qualitative and quantitative results show that the proposed method is significantly superior to the state-of-the-art methods in handling the image data that are with high variability."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://link.springer.com/content/pdf/10.1007/s00500-020-05073-6.pdf'
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
