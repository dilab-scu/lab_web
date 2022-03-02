---
title: "Zero-Shot Learning via Structure-Aligned Generative Adversarial Network."
authors:
- ChenweiTang
- ZhenanHe,
- YunxiaLi,
- admin
date: "2021-06-09T00:00:00Z"
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

abstract: "In this article, we propose a structure-aligned generative adversarial network framework to improve zero-shot learning (ZSL) by mitigating the semantic gap, domain shift, and hubness problem. The proposed framework contains two parts, i.e., a generative adversarial network with a softmax classifier part, and a structure-aligned part. In the first part, the generative adversarial network aims at generating pseudovisual features through the guiding generator and discriminator play the minimax two-player game together. At the same time, the softmax classifier is committed to increasing the interclass distance and reducing intraclass distance. Then, the harmful effect of domain shift and hubness problems can be mitigated. In another part, we introduce a structure-aligned module where the structural consistency between visual space and semantic space is learned. By aligning the structure between visual space and semantic space, the semantic gap between them can be bridged. The performance of classification is improved when the structure-aligned visual-semantic embedding space is transferred to the unseen classes. Our framework reformulates the ZSL as a standard fully supervised classification task using the pseudovisual features of unseen classes. Extensive experiments conducted on five benchmark data sets demonstrate that the proposed framework significantly outperforms state-of-the-art methods in both conventional and generalized settings."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9449653'
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
