---
title: "Efficient Pure Exploration for Combinatorial Bandits with Semi-Bandit Feedback"

# Authors
authors: [admin, Mojmír Mutný, Johannes Kirschner, Andreas Krause]

date: "2021-01-21"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 32nd International Conference on Algorithmic Learning Theory
publication_short: ALT 2021

abstract: Combinatorial bandits with semi-bandit feedback generalize multi-armed bandits, where the agent chooses sets of arms and observes a noisy reward for each arm contained in the chosen set. The action set satisfies a given structure such as forming a base of a matroid or a path in a graph. We focus on the pure-exploration problem of identifying the best arm with fixed confidence, as well as a more general setting, where the structure of the answer set differs from the one of the action set. Using the recently popularized game framework, we interpret this problem as a sequential zero-sum game and develop a CombGame meta-algorithm whose instances are asymptotically optimal algorithms with finite time guarantees. In addition to comparing two families of learners to instantiate our meta-algorithm, the main contribution of our work is a specific oracle efficient instance for best-arm identification with combinatorial actions. Based on a projection-free online learning algorithm for convex polytopes, it is the first computationally efficient algorithm which is asymptotically optimal and has competitive empirical performance.

tags: ["Combinatorial bandits", "Transductive bandits", "Best-arm identification", "Semi-bandit feedback", "Game algorithm", "Fixed confidence"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
  - name: Arxiv
    url: 'https://arxiv.org/abs/2101.08534'

url_pdf: 'https://arxiv.org/pdf/2101.08534'
url_slides: 'alt2021talkpecb.pdf'
url_video: 'https://www.youtube.com/watch?v=EZHhN4YQh4U'
#url_code: ''
#url_poster: ''

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
