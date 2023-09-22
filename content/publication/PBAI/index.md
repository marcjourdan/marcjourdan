---
title: "On the Complexity of Differentially Private Best-Arm Identification with Fixed Confidence"

# Authors
authors: [achraf, admin, aymen, debabrota]

date: "2023-09-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: Conference on Neural Information Processing Systems
publication_short: NeurIPS 2023

abstract: Best Arm Identification (BAI) problems are progressively used for data-sensitive applications, such as designing adaptive clinical trials, tuning hyper-parameters, and conducting user studies to name a few. Motivated by the data privacy concerns invoked by these applications, we study the problem of BAI with fixed confidence under ϵ-global Differential Privacy (DP). First, to quantify the cost of privacy, we derive a lower bound on the sample complexity of any δ-correct BAI algorithm satisfying ϵ-global DP. Our lower bound suggests the existence of two privacy regimes depending on the privacy budget ϵ. In the high-privacy regime (small ϵ), the hardness depends on a coupled effect of privacy and a novel informationtheoretic quantity, called the Total Variation Characteristic Time. In the low-privacy regime (large ϵ), the sample complexity lower bound reduces to the classical nonprivate lower bound. Second, we propose AdaP-TT, an ϵ-global DP variant of the Top Two algorithm. AdaP-TT runs in arm-dependent adaptive episodes and adds Laplace noise to ensure a good privacy-utility trade-off. We derive an asymptotic upper bound on the sample complexity of AdaP-TT that matches with the lower bound up to multiplicative constants in the high-privacy regime. Finally, we provide an experimental analysis of AdaP-TT that validates our theoretical results.

tags: ["Differential privacy", "Multi-armed bandits", "Best-arm identification", "Fixed confidence", "Top Two algorithm"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2206.05979'

url_pdf: 'https://arxiv.org/pdf/2309.02202'
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
