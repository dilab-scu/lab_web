---
title: "Unsupervised Multi-Manifold Clustering by Learning Deep Representation."
authors:
- D.Chen
- admin
- Z.Yi
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

abstract: "In this paper, we propose a novel deep manifold clustering(DMC) method for learning effective deep representationsand partitioning a dataset into clusters where each clustercontains data points from a single nonlinear manifold. Dif-ferent from other previous research efforts, we adopt deepneural network to classify and parameterize unlabeled datawhich lie on multiple manifolds. Firstly, motivated by theobservation that nearby points lie on the local of manifoldshould possess similar representations, a locality preserv-ing objective is defined to iteratively explore data relationand learn structure preserving representations. Secondly, byfinding the corresponding cluster centers from the represen-tations, a clustering-oriented objective is then proposed toguide the model to extract both discriminative and cluster-specific representations. Finally, by integrating two objectivesinto a single model with a unified cost function and opti-mizing it by using back propagation, we can obtain not onlymore powerful representations, but also more precise clustersof data. In addition, our model can be intuitively extendedto cluster out-of-sample datum. The experimental results andcomparisons with existing state-of-the-art methods show thatthe proposed method consistently achieves the best perfor-mance on various benchmark datasets"

# Summary. An optional shortened abstract.
summary:

tags:

featured: false

links:
url_pdf: 'https://www.aaai.org/ocs/index.php/WS/AAAIW17/paper/download/15099/14689'
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
