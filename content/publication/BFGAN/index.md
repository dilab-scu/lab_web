---
title: "BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation"
authors:
- DayihengLiu
- JieFu
- QianQu
- admin
date: "2020-04-07T00:00:00Z"
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

abstract: "Incorporating prior knowledge like lexical constraints into the model's output to generate meaningful and coherent sentences has many applications in dialogue system, machine translation, image captioning, etc. However, existing auto-regressive models incrementally generate sentences from left to right via beam search, which makes it difficult to directly introduce lexical constraints into the generated sentences. In this paper, we propose a new algorithmic framework, dubbed BFGAN, to address this challenge. Specifically, we employ a backward generator and a forward generator to generate lexically constrained sentences together, and use a discriminator to guide the joint training of two generators by assigning them reward signals. Due to the difficulty of BFGAN training, we propose several training techniques to make the training process more stable and efficient. Our extensive experiments on three large-scale datasets with human evaluation demonstrate that BFGAN has significant improvements over previous methods."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/document/8846084'
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
