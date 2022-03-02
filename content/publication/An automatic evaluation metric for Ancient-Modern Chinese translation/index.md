---
title: "An automatic evaluation metric for Ancient-Modern Chinese translation."
authors:
- KexinYang
- DayihengLiu
- QianQu
- YongshengSang
- admin
date: "2021-04-07T00:00:00Z"
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

abstract: "As a written language used for thousands of years, Ancient Chinese has some special characteristics like complex semantics as polysemy and the one-to-many alignment with Modern Chinese. Thus it may be translated in a large number of fully different but equally correct ways. In the absence of multiple references, reference-dependent evaluations like Bilingual Evaluation Understudy (BLEU) cannot identify potentially correct translation results. The explore on automatic evaluation of Ancient-Modern Chinese Translation is completely lacking. In this paper, we proposed an automatic evaluation metric for Ancient-Modern Chinese Translation called DTE (Dual-based Translation Evaluation), which can be used to evaluate one-to-many alignment in the absence of multiple references. When using DTE to evaluate, we found that the proper nouns often could not be correctly translated. Hence, we designed a new word segmentation method to improve the translation of proper nouns without increasing the size of the model vocabulary. Experiments show that DTE outperforms several general evaluations in terms of similarity to the evaluation of human experts. Meanwhile, the new word segmentation method promotes the Ancient-Modern Chinese translation models perform better on proper nouns’ translation, and get higher scores on both BLEU and DTE."

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
#url_pdf: 'https://github.com/dayihengliu/a2m_chineseNMT'
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
