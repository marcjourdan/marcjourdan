---
title: "Dealing with Unknown Variances in Best-Arm Identification"

# Authors
authors: [admin, remy, emilie]

date: "2023-01-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

publication: The 34th International Conference on Algorithmic Learning Theory
publication_short: ALT 2023

abstract: The problem of identifying the best arm among a collection of items having Gaussian rewards distribution is well understood when the variances are known. Despite its practical relevance for many applications, few works studied it for unknown variances. In this paper we introduce and analyze two approaches to deal with unknown variances, either by plugging in the empirical variance or by adapting the transportation costs. In order to calibrate our two stopping rules, we derive new time-uniform concentration inequalities, which are of independent interest. Then, we illustrate the theoretical and empirical performances of our two sampling rule wrappers on Track-and-Stop and on a Top Two algorithm. Moreover, by quantifying the impact on the sample complexity of not knowing the variances, we reveal that it is rather small.

tags: ["Multi-armed bandits", "Best-arm identification", "Gaussian Bandits", "Unknown Variances", "Fixed confidence"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#  - name: Arxiv
#    url: 'https://arxiv.org/abs/2210.00974'

url_pdf: 'https://arxiv.org/pdf/2210.00974'
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
