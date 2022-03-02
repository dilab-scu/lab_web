---
title: "Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation."
authors:
- DayihengLiu
- YeyunGong
- YuYan
- JieFu
- BoShao
- DaxinJiang
- admin
- NanDuan

date: "2020-04-07T00:00:00Z"
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

abstract: "News headline generation aims to produce a short sentence to attract readers to read the news. One news article often contains multiple keyphrases that are of interest to different users, which can naturally have multiple reasonable headlines. However, most existing methods focus on the single headline generation. In this paper, we propose generating multiple headlines with keyphrases of user interests, whose main idea is to generate multiple keyphrases of interest to users for the news first, and then generate multiple keyphrase-relevant headlines. We propose a multi-source Transformer decoder, which takes three sources as inputs: (a) keyphrase, (b) keyphrase-filtered article, and (c) original article to generate keyphrase-relevant, high-quality, and diverse headlines. Furthermore, we propose a simple and effective method to mine the keyphrases of interest in the news article and build a first large-scale keyphrase-aware news headline corpus, which contains over 180K aligned triples of <news article, headline, keyphrase>. Extensive experimental comparisons on the real-world dataset show that the proposed method achieves state-of-the-art results in terms of quality and diversity."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://aclanthology.org/2020.emnlp-main.505.pdf'
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
