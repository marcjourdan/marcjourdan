---
title: "Pareto Set Identification with Posterior Sampling"

# Authors
authors: [cyrille, admin, emilie]

date: "2024-11-07"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

publication: 
publication_short: 

abstract: The problem of identifying the best answer among a collection of items having real-valued distribution is well-understood. Despite its practical relevance for many applications, fewer works have studied its extension when multiple and potentially conflicting metrics are available to assess an item's quality. Pareto set identification (PSI) aims to identify the set of answers whose means are not uniformly worse than another. This paper studies PSI in the transductive linear setting with potentially correlated objectives. Building on posterior sampling in both the stopping and the sampling rules, we propose the PSIPS algorithm that deals simultaneously with structure and correlation without paying the computational cost of existing oracle-based algorithms. Both from a frequentist and Bayesian perspective, PSIPS is asymptotically optimal. We demonstrate its good empirical performance in real-world and synthetic instances. 

tags: ["Multi-armed bandits", "Pure exploration", "Pareto set identification", "Posterior sampling"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2206.05979'

url_pdf: 'https://arxiv.org/pdf/2411.04939'
#url_poster: ''
#url_video: ''
#url_slides: ''
#url_code: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""

---
