---
title: "Matrix completion by least-square, low-rank, and sparse self-representations"
authors:
- admin
- Tommy W.S. Chow
date: "2017-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition"
publication_short: ""

abstract: "Conventional matrix completion methods are generally based on rank minimization. These methods assume that the given matrix is of low-rank and the data points are drawn from a single subspace of low-dimensionality. Therefore they are not effective in completing matrices where the data are drawn from multiple subspaces. In this paper, we establish a novel matrix completion framework that is based on self-representation. Specifically, least-square, low-rank, and sparse self-representations based matrix completion algorithms are provided. The underlying idea is that one data point can be efficiently reconstructed by other data points belonging to a common subspace, where the missing entries are recovered so as to fit the common subspace. The proposed algorithms actually maximize the weighted correlations among the columns of a given matrix. We prove that the proposed algorithms are approximations for rank-minimization of the incomplete matrix. In addition, they are able to complete high-rank or even full-rank matrices when the data are drawn from multiple subspaces. Comparative studies are conducted on synthetic datasets, natural image inpainting tasks, temperature prediction task, and collaborative filtering tasks. The results show that the proposed algorithms often outperform other state-of-the-art algorithms in various tasks."

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0031320317302030
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


