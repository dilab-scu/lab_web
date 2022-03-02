---
title: "POS-Constrained Parallel Decoding for Non-autoregressive Generation."
authors:
- KexinYang
- WenqiangLei
- DayihengLiu
- WeizhenQi
- admin
date: "2021-08-01T00:00:00Z"
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

abstract: "The multimodality problem has become a major challenge of existing non-autoregressive generation (NAG) systems. A common solution often resorts to sequence-level knowledge distillation by rebuilding the training dataset through autoregressive generation (hereinafter known as “teacher AG”). The success of such methods may largely depend on a latent assumption, i.e., the teacher AG is superior to the NAG model. However, in this work, we experimentally reveal that this assumption does not always hold for the text generation tasks like text summarization and story ending generation. To provide a feasible solution to the multimodality problem of NAG, we propose incorporating linguistic structure (Part-of-Speech sequence in particular) into NAG inference instead of relying on teacher AG. More specifically, the proposed POS-constrained Parallel Decoding (POSPD) method aims at providing a specific POS sequence to constrain the NAG model during decoding. Our experiments demonstrate that POSPD consistently improves NAG models on four text generation tasks to a greater extent compared to knowledge distillation. This observation validates the necessity of exploring the alternatives for sequence-level knowledge distillation."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://aclanthology.org/2021.acl-long.467.pdf'
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
