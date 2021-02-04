---
title: "RikiNet: Reading Wikipedia Pages for Natural Question Answering."
authors:
- DayihengLiu
- YeyunGong
- JieFu
- YuYan
- JiushengChen
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

abstract: "Reading   long   documents   to   answer   open-domain questions remains challenging in nat-ural language understanding. In this paper, weintroduce a new model, called RikiNet, whichreads Wikipedia pages for natural question an-swering.    RikiNet  contains  a  dynamic  para-graph  dual-attention  reader  and  a  multi-levelcascaded answer predictor. The reader dynam-ically  represents  the  document  and  questionby utilizing a set of complementary attentionmechanisms.  The representations are then fedinto the predictor to obtain the span of the shortanswer, the paragraph of the long answer, andthe  answer  type  in  a  cascaded  manner.   Onthe  Natural  Questions  (NQ)  dataset,  a  singleRikiNet achieves 74.3 F1 and 57.9 F1 on long-answer  and  short-answer  tasks.   To  our  bestknowledge, it is the first single model that out-performs the single human performance.  Fur-thermore,  an  ensemble  RikiNet  obtains  76.1F1  and  61.3  F1  on  long-answer  and  short-answer tasks, achieving the best performanceon the official NQ leaderboard"

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://www.aclweb.org/anthology/2020.acl-main.604.pdf'
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
