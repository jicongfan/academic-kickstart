---
title: "Accelerated low-rank representation for subspace clustering and semi-supervised classification on large-scale data"
authors:
- admin
- Zhaoyang Tian
- Mingbo Zhao
- Tommy WS Chow
date: "2018-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Neural Networks"
publication_short: ""

abstract: "The scalability of low-rank representation (LRR) to large-scale data is still a major research issue, because it is extremely time-consuming to solve singular value decomposition (SVD) in each optimization iteration especially for large matrices. Several methods were proposed to speed up LRR, but they are still computationally heavy, and the overall representation results were also found degenerated. In this paper, a novel method, called accelerated LRR (ALRR) is proposed for large-scale data. The proposed accelerated method integrates matrix factorization with nuclear-norm minimization to find a low-rank representation. In our proposed method, the large square matrix of representation coefficients is transformed into a significantly smaller square matrix, on which SVD can be efficiently implemented. The size of the transformed matrix is not related to the number of data points and the optimization of ALRR is linear with the number of data points. The proposed ALRR is convex, accurate, robust, and efficient for large-scale data. In this paper, ALRR is compared with state-of-the-art in subspace clustering and semi-supervised classification on real image datasets. The obtained results verify the effectiveness and superiority of the proposed ALRR method."

# Summary. An optional shortened abstract.
summary: 

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0893608018300145
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

