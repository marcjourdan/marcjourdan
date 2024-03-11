---
title: "LAS Seminar: Best-Arm Identification with Top Two Algorithms"
event: 'LAS Seminar'
event_url: 'https://las.inf.ethz.ch/'

location: 'ETH Zurich'
address:
  street: ''
  city: 'Zurich'
  region: ''
  postcode: ''
  country: 'Switzerland'

summary: ''
abstract: 'Top Two algorithms arose as an adaptation of Thompson sampling to best arm identification in multi-armed bandit models, for parametric families of arms. They select the next arm to sample from among two candidate arms, a leader and a challenger. Despite their
 simplicity and good empirical performance, theoretical guarantees for fixed-confidence best arm identification have only been obtained asymptotically (i.e. vanishing error level) when the arms are Gaussian with known variances. In this talk, I will present
 recent advances on the theoretical understanding of Top Two algorithms, and sketch remaining open problems. Our first contribution is a general analysis of Top Two methods in the asymptotic regime, which identifies desirable properties of the leader, the challenger,
 and the (possibly non-parametric) distributions of the arms. As a result, we obtain theoretically supported Top Two algorithms for best arm identification with bounded distributions. Our second contribution is to derive the first non-asymptotic upper bound
 on the expected sample complexity of a Top Two algorithm, which holds for any error level and any instance having a unique best arm. In particular, we identify sufficient properties of the leader (seen as a regret minimization algorithm) for it to hold. As
 a consequence, we propose the TTUCB (Top Two UCB) algorithm which builds on the UCB algorithm and uses tracking instead of sampling to choose between the leader and the challenger.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-02-01T11:00:00Z"
#date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---


