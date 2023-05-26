---
title: "An ε-Best-Arm Identification Algorithm for Fixed-Confidence and Beyond"

# Authors
authors: [admin, remy, emilie]

date: "2023-05-25"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

publication: Preprint 2023
publication_short: Preprint 2023

abstract: We propose EB-TCε, a novel sampling rule for ε-best arm identification in stochastic bandits. It is the first instance of Top Two algorithm analyzed for approximate best arm identification. EB-TCε is an *anytime* sampling rule that can therefore be employed without modification for fixed confidence or fixed budget identification (without prior knowledge of the budget). We provide three types of theoretical guarantees for EB-TCε. First, we prove bounds on its expected sample complexity in the fixed confidence setting, notably showing its asymptotic optimality in combination with an adaptive tuning of its exploration parameter. We complement these findings with upper bounds on its probability of error at any time and for any error parameter, which further yield upper bounds on its simple regret at any time. Finally, we show through numerical simulations that EB-TCε performs favorably compared to existing algorithms, in different settings.

tags: ["Multi-armed bandits", "Pure exploration", "Epsilon-best-arm identification", "Top Two algorithm", "Anytime"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2210.05431'

url_pdf: 'https://arxiv.org/abs/2305.16041'
url_poster: 'posterttebai.pdf'
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
