---
title: "Hierarchical Regulated Iterative Network for Joint Task of Music Detection and Music Relative Loudness Estimation."
authors:
- BijueJia
- XiPeng
- YaoChen
- ShenglanYang
- admin
date: "2020-10-13T00:00:00Z"
doi: "https://doi.org/10.1109/TASLP.2020.3030484"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing"
publication_short: ""

abstract: "One practical requirement of the music copyright management is the estimation of music relative loudness, which is mostly ignored in existing music detection works. To solve this problem, we study the joint task of music detection and music relative loudness estimation. To be specific, we observe that the joint task has two characteristics, i.e., temporality and hierarchy, which could facilitate to obtain the solution. For example, a tiny fragment of audio is temporally related to its neighbor fragments because they may all belong to the same event, and the event classes of the fragment in the two tasks have a hierarchical relationship. Based on the above observation, we reformulate the joint task as hierarchical event detection and localization problem. To solve this problem, we further propose Hierarchical Regulated Iterative Networks (HRIN), which includes two variants, termed as HRIN-r and HRIN-cr, which are based on recurrent and convolutional recurrent modules. To enjoy the joint task's characteristics, our models employ an iterative framework to achieve encouraging capability in temporal modeling while designing three hierarchical violation penalties to regulate hierarchy. Extensive experiments on the currently largest dataset (i.e., OpenBMAT) show that the promising performance of our HRIN in the segment-level and event-level evaluations."

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