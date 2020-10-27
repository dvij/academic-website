---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The NodeHopper: Enabling Low Latency Ranking with Constraints via a Fast Dual
  Solver'
subtitle: ''
summary: ''
authors:
- Anton Zhernov
- Krishnamurthy Dj Dvijotham
- Ivan Lobov
- Dan A. Calian
- Michelle Gong
- Natarajan Chandrashekar
- Timothy A. Mann
tags:
- '"ranking"'
- '"scalability"'
- '"linear programming"'
categories: []
date: '2020-01-01'
lastmod: 2020-10-27T17:23:50Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-27T17:24:59.731951Z'
publication_types:
- '1'
abstract: Modern recommender systems need to deal with multiple objectives like balancing
  user engagement with recommending diverse and fresh content. An appealing way to
  optimally trade these off is by imposing constraints on the ranking according to
  which items are presented to a user. This results in a constrained ranking optimization
  problem that can be solved as a linear program (LP). However, off-the-shelf LP solvers
  are unable to meet the severe latency constraints in systems that serve live traffic.
  To address this challenge, we exploit the structure of the dual optimization problem
  to develop a fast solver. We analyze theoretical properties of our solver and show
  experimentally that it is able to solve constrained ranking problems on synthetic
  and real-world recommendation datasets an order of magnitude faster than off-the-shelf
  solvers, thereby enabling their deployment under severe latency constraints.
publication: '*Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
url_pdf: https://doi.org/10.1145/3394486.3403181
doi: 10.1145/3394486.3403181
---
