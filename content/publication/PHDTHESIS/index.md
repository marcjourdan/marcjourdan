---
title: "Solving Pure Exploration Problems with the Top Two Approach"

# Authors
authors: [admin]

date: "2024-06-14"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

publication: Université de Lille
publication_short: Université de Lille

abstract: In pure exploration problems for stochastic multi-armed bandits, the objective is to answer inquiries regarding a set of unknown distributions (modeling for example the efficacy of a treatment) from which we can collect samples (measure its effect), and subsequently provide guarantees on the candidate answer. 
 The archetypal example is the best arm identification problem, in which the agent aims at identifying the arm with the highest mean. 

 This thesis delves into the class of Top Two algorithms, wherein a leader is pitted against a challenger, directing subsequent sampling efforts to validate the superiority of the leader. 
 We introduce a unified definition of the Top Two approach, putting forward four key components. 
 Given their simplicity, interpretability, generalizability, and versatility, Top Two algorithms are promising for widespread adoption among practitioners. 
 This thesis endeavors to establish the Top Two approach as a principled methodology offering nearly optimal theoretical guarantees alongside state-of-the-art empirical performance.

 We address several stochastic multi-armed bandits settings, such as various classes of distributions or structural assumptions on the means.
 We also study different pure exploration problems, including the identification of the best arm or one of acceptable quality.
 The principal contribution of this thesis lies in establishing theoretical guarantees for the Top Two approach across several performance metrics. 
 In the fixed-confidence setting, we prove that many Top Two algorithms have an asymptotically optimal expected sample complexity (number of collected samples when the confidence level goes to one). 
 In the anytime setting, we propose a Top Two algorithm which has guarantees on the probability of misidentifying a good enough arm at any time.

tags: ["Multi-armed bandits", "Best-arm identification", "Pure exploration"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2210.00974'

url_pdf: 'phdthesis.pdf'
#url_poster: ''
url_video: 'https://youtu.be/tTCDza9J6PY'
url_slides: 'phddefense.pdf'
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
