---
title: "Optimal Best Arm Identification under Differential Privacy"

# Authors
authors: [admin, achraf]

date: "2025-09-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: Conference on Neural Information Processing Systems
publication_short: NeurIPS 2025

abstract: Best Arm Identification (BAI) algorithms are deployed in data-sensitive applications, such as adaptive clinical trials or user studies. Driven by the privacy concerns of these applications, we study the problem of fixed-confidence BAI under global Differential Privacy (DP) for Bernoulli distributions. While numerous asymptotically optimal BAI algorithms exist in the non-private setting, a significant gap remains between the best lower and upper bounds in the global DP setting. This work reduces this gap to a small multiplicative constant, for any privacy budget ϵ. First, we provide a tighter lower bound on the expected sample complexity of any δ-correct and ϵ-global DP strategy. Our lower bound replaces the Kullback–Leibler (KL) divergence in the transportation cost used by the non-private characteristic time with a new information-theoretic quantity that optimally trades off between the KL divergence and the Total Variation distance scaled by ϵ. Second, we introduce a stopping rule based on these transportation costs and a private estimator of the means computed using an arm-dependent geometric batching. En route to proving the correctness of our stopping rule, we derive concentration results of independent interest for the Laplace distribution and for the sum of Bernoulli and Laplace distributions. Third, we propose a Top Two sampling rule based on these transportation costs. For any budget ϵ, we show an asymptotic upper bound on its expected sample complexity that matches our lower bound to a multiplicative constant smaller than 8. Our algorithm outperforms existing δ-correct and ϵ-global DP BAI algorithms for different values of ϵ.

tags: ["Differential privacy", "Multi-armed bandits", "Best-arm identification", "Fixed confidence", "Top Two algorithm"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2206.05979'

url_pdf: 'https://arxiv.org/pdf/2510.17348'
url_poster: 'posterdptt.pdf'
url_video: 'https://neurips.cc/virtual/2025/loc/san-diego/poster/115187'
# url_slides: ''
url_code: 'https://openreview.net/attachment?id=y4AXO2pFAh&name=supplementary_material'


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
