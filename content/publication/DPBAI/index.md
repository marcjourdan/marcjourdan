---
title: "Differentially Private Best-Arm Identification"

# Authors
authors: [achraf, admin, aymen, debabrota]

date: "2024-06-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: 
publication_short: 

abstract: Best Arm Identification (BAI) problems are progressively used for data-sensitive applications, such as designing adaptive clinical trials, tuning hyper-parameters, and conducting user studies. Motivated by the data privacy concerns invoked by these applications, we study the problem of BAI with fixed confidence in both the local and central models, i.e. ϵ-local and ϵ-global Differential Privacy (DP). First, to quantify the cost of privacy, we derive lower bounds on the sample complexity of any δ-correct BAI algorithm satisfying ϵ-global DP or ϵ-local DP. Our lower bounds suggest the existence of two privacy regimes. In the high-privacy regime, the hardness depends on a coupled effect of privacy and novel information-theoretic quantities involving the Total Variation. In the low-privacy regime, the lower bounds reduce to the non-private lower bounds. We propose ϵ-local DP and ϵ-global DP variants of a Top Two algorithm, namely CTB-TT and AdaP-TT*, respectively. For ϵ-local DP, CTB-TT is asymptotically optimal by plugging in a private estimator of the means based on Randomised Response. For ϵ-global DP, our private estimator of the mean runs in arm-dependent adaptive episodes and adds Laplace noise to ensure a good privacy-utility trade-off. By adapting the transportation costs, the expected sample complexity of AdaP-TT* reaches the asymptotic lower bound up to multiplicative constants.

tags: ["Differential privacy", "Multi-armed bandits", "Best-arm identification", "Fixed confidence", "Top Two algorithm"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2206.05979'

url_pdf: 'https://arxiv.org/pdf/2406.06408'
#url_poster: 'posterprivatebai.pdf'
#url_video: 'https://neurips.cc/virtual/2023/poster/71838'
#url_slides: 'slidespbai.pdf'
url_code: 'https://github.com/achraf-azize/DP-BAI'


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
