---
title: "Matrix completion via sparse factorization solved by accelerated proximal alternating linearized minimization"
authors:
- admin
- Mingbo Zhao
- Tommy W.S. Chow
date: "2018-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Big Data"
publication_short: ""

abstract: "Classical matrix completion methods are not effective in recovering missing entries of data drawn from multiple subspaces because the matrices are often of high-rank. Recently a few advanced matrix completion methods were proposed to solve the problem but they are not scalable to large matrices and big data problems. This paper proposes a sparse factorization method for matrix completion on multiple-subspace data. The method factorizes the given incomplete matrix into a dense matrix and a sparse matrix, while the factorization errors of the observed entries are minimized. To solve the optimization problem, an accelerated proximal alternating linearized minimization (APALM) algorithm is proposed. As a non-trivial task owing to the alternation, linearization, nonconvexity, and extrapolation, the convergence of APALM is proved. APALM can solve a large class of optimization problems such as matrix factorization with nonsmooth regularizations. In addition, we show that, to recover an m×n matrix consisting of data drawn from k subspaces of dimension r , the number of observed entries required in our matrix completion method is O(nrlogklogn) while that in conventional methods is O(nrklogn) , which theoretically proves the superiority of our method on multiple-subspace data and high-rank matrices. The proposed matrix completion method is compared with state-of-the-art on synthetic data and real collaborative filtering problems. The experimental results corroborate that the proposed method can handle large matrices efficiently and provide high recovery accuracy."

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/8469061
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


