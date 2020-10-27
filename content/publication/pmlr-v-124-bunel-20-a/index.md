---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Lagrangian Decomposition for Neural Network Verification
subtitle: ''
summary: ''
authors:
- Rudy Bunel
- Alessandro De Palma
- Alban Desmaison
- Krishnamurthy Dvijotham
- Pushmeet Kohli
- Philip Torr
- M. Pawan Kumar
tags: []
categories: []
date: '2020-08-01'
lastmod: 2020-10-27T17:23:51Z
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
publishDate: '2020-10-27T17:25:00.460865Z'
publication_types:
- '1'
abstract: 'A fundamental component of neural network verification is the computation
  of bounds on the values their outputs can take. Previous methods have either used
  off-the-shelf solvers, discarding the problem structure, or relaxed the problem
  even further, making the bounds unnecessarily loose. We propose a novel approach
  based on Lagrangian Decomposition. Our formulation admits an efficient supergradient
  ascent algorithm, as well as an improved proximal algorithm. Both the algorithms
  offer three advantages: (i) they yield bounds that are provably at least as tight
  as previous dual algorithms relying on Lagrangian relaxations; (ii) they are based
  on operations analogous to forward/backward pass of neural networks layers and are
  therefore easily parallelizable, amenable to GPU implementation and able to take
  advantage of the convolutional structure of problems; and (iii) they allow for anytime
  stopping while still providing valid bounds. Empirically, we show that we obtain
  bounds comparable with off-the-shelf solvers in a fraction of their running time,
  and obtain tighter bounds in the same time as previous dual algorithms. This results
  in an overall speed-up when employing the bounds for formal verification. Code for
  our algorithms is available at https://github.com/oval-group/decomposition-plnn-bounds.'
publication: '*PMLR*'
url_pdf: http://proceedings.mlr.press/v124/bunel20a.html
---
