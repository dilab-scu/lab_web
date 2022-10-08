---
title: "Deep Spectral Representation Learning From Multi-View Data."
authors:
- ZhenyuHuang
- Joey TianyiZhou
- HongyuanZhu
- ChangqingZhang
- XiPeng
- admin
date: "2021-06-03T00:00:00Z"
doi: "https://doi.org/10.1109/TIP.2021.3083072"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: ""

abstract: "Multi-view representation learning (MvRL) aims to learn a consensus representation from diverse sources or domains to facilitate downstream tasks such as clustering, retrieval, and classification. Due to the limited representative capacity of the adopted shallow models, most existing MvRL methods may yield unsatisfactory results, especially when the labels of data are unavailable. To enjoy the representative capacity of deep learning, this paper proposes a novel multi-view unsupervised representation learning method, termed as Multi-view Laplacian Network (MvLNet), which could be the first deep version of the multi-view spectral representation learning method. Note that, such an attempt is nontrivial because simply combining Laplacian embedding (i.e., spectral representation) with neural networks will lead to trivial solutions. To solve this problem, MvLNet enforces an orthogonal constraint and reformulates it as a layer with the help of Cholesky decomposition. The orthogonal layer is stacked on the embedding network so that a common space could be learned for consensus representation. Compared with numerous recent-proposed approaches, extensive experiments on seven challenging datasets demonstrate the effectiveness of our method in three multi-view tasks including clustering, recognition, and retrieval. The source code could be found at www.pengxi.me."

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