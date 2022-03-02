---
title: "Zero-Shot Learning by Mutual Information Estimation and Maximization."
authors:
- ChenweiTang
- XueYang
- admin
- ZhenanHe
date: "2020-01-14T00:00:00Z"
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

abstract: "The key of zero-shot learning is to use the visual-semantic embedding to transfer the knowledge from seen classes to unseen classes. In this paper, we propose to build the visual-semantic embedding by maximizing the mutual information between visual features and corresponding attributes. Then, the mutual information between visual and semantic features can be utilized to guide the knowledge transfer from seen domain to unseen domain. Since we are primarily interested in maximizing mutual information, we introduce the noise-contrastive estimation to calculate lower-bound value of mutual information. Through the noise-contrastive estimation, we reformulate zero-shot learning as a binary classification problem, i.e., classifying the matching visual-semantic pairs (positive samples) and mismatching visual-semantic pairs (negative/noise samples). Experiments conducted on five datasets demonstrate that the proposed mutual information estimators outperforms current state-of-the-art methods both in conventional and generalized zero-shot learning settings."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://pdf.sciencedirectassets.com/271505/1-s2.0-S0950705120X00074/1-s2.0-S0950705120300101/main.pdf'
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
