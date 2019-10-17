---
title: "Factor group sparse regularization for efficient low-rank matrix recovery"
authors:
- admin
- Lijun Ding
- Yudong Chen
- Madeleine Udell
date: "2019-12-01"
doi: ""



# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: NeurIPS 2019
publication_short: NeurIPS 2019

abstract: "This paper develops a new class of nonconvex regularizers for low-rank matrix recovery.
Many regularizers are motivated as convex relaxations of the matrix rank function.
Our new factor group-sparse regularizers are motivated as a relaxation of the number of nonzero columns in a factorization of the matrix. These nonconvex regularizers are sharper than the nuclear norm; indeed, we show they are related to Schatten-p norms with arbitrarily small 0<p<1.
Moreover, these factor group-sparse regularizers can be written in a factored form that enables efficient and effective nonconvex optimization; notably, the method does not use singular value decomposition.
We provide generalization error bounds for low-rank matrix completion which show improved upper bounds for Schatten-p norm reglarization as p decreases. Compared to the max norm and the factored formulation of the nuclear norm, factor group-sparse regularizers are more efficient, accurate,
and robust to the initial guess of rank. Experiments show promising performance of factor group-sparse regularization for low-rank matrix completion and robust principal component analysis."



tags:
- Source Themes
featured: true

links:

url_pdf: '#'
url_code: 'https://github.com/udellgroup/Codes-of-FGSR-for-effecient-low-rank-matrix-recovery'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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


