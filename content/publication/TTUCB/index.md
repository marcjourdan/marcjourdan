---
title: "Finite-time Analysis of a UCB-based Top Two Algorithm"

# Authors
authors: [admin, Rémy Degenne]

date: "2022-10-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: Preprint 2022
publication_short: Preprint 2022

abstract: A Top Two sampling rule for bandit identification is a method which selects the next arm to sample from among two candidate arms, a leader and a challenger. Due to their simplicity and good empirical performance, they have received increased attention in recent years. For fixed-confidence best arm identification, theoretical guarantees for Top Two methods have only been obtained in the asymptotic regime, when the error level vanishes. We derive the first finite-time upper bound on the expected sample complexity of a Top Two algorithm holding for any error level. Our analysis highlights sufficient properties for a deterministic regret minimization algorithm to be used as leader. They are satisfied by the UCB algorithm and our proposed UCB-based Top Two algorithm enjoys simultaneously finite-time guarantees, low computational cost and competitive empirical performance.

tags: ["Multi-armed bandits", "Best-arm identification", "Gaussian Bandits", "Top Two algorithm", "Fixed confidence", "Finite-time"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2210.00974'

url_pdf: 'https://arxiv.org/pdf/2210.xxxxx'
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
