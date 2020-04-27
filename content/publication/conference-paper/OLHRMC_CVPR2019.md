---
title: "Online high-rank matrix completion"
authors:
- admin
- Madeleine Udell
date: "2019-06-01"
doi: ""

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 3


# Schedule page publish date (NOT publication's date).
# publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: CVPR 2019 (oral)
publication_short: 

abstract: "Recent advances in matrix completion enable data imputation in full-rank matrices by exploiting low dimensional (nonlinear) latent structure. In this paper, we develop a new model for high rank matrix completion (HRMC), together with batch and online methods to fit the model and out-of-sample extension to complete new data. The method works by (implicitly) mapping the data into a high dimensional polynomial feature space using the kernel trick; importantly, the data occupies a low dimensional subspace in this feature space, even when the original data matrix is of full-rank. The online method can handle streaming or sequential data and adapt to non-stationary latent structure, and enjoys much lower space and time complexity than previous methods for HRMC. For example, the time complexity is reduced from O(n3) to O(r3), where n is the number of data points, r is the matrix rank in the feature space, and r ≪ n. We also provide guidance on sampling rate required for these methods to succeed. Experimental results on synthetic data and motion data validate the performance of the proposed methods."

# Summary. An optional shortened abstract.
summary: 

tags:

featured: true

links:

url_pdf: http://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_Online_High_Rank_Matrix_Completion_CVPR_2019_paper.pdf
url_code: 'https://github.com/jicongfan/Online-high-rank-matrix-completion'
# url_dataset: '#'
url_poster: 'poster/OLHRMC.pdf'
# url_project: ''
# url_slides: '#'


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


