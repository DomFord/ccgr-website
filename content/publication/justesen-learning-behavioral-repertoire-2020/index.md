---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Learning a Behavioral Repertoire from Demonstrations
subtitle: ''
summary: ''
authors:
- Niels Justesen
- Miguel Gonzalez-Duque
- Daniel Cabarcas
- Jean-Baptiste Mouret
- Sebastian Risi
tags: []
categories: []
date: '2020-08-01'
lastmod: 2021-02-01T14:26:25+01:00
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
publishDate: '2021-02-01T13:26:25.161883Z'
publication_types:
- '1'
abstract: Imitation Learning (IL) is a machine learning approach to learn a policy
  from a set of demonstrations. IL can be useful to kick-start learning before applying
  reinforcement learning (RL) but it can also be useful on its own, e.g. to learn
  to imitate human players in video games. Despite the success of systems that use
  IL and RL, how such systems can adapt in-between game rounds is a neglected area
  of study but an important aspect of many strategy games. In this paper, we present
  a new approach called Behavioral Repertoire Imitation Learning (BRIL) that learns
  a repertoire of behaviors from a set of demonstrations by augmenting the state-action
  pairs with behavioral descriptions. The outcome of this approach is a single neural
  network policy conditioned on a behavior description that can be precisely modulated.
  We apply this approach to train a policy on 7,777 human demonstrations for the build-order
  planning task in StarCraft II. Dimensionality reduction is applied to construct
  a low-dimensional behavioral space from a high-dimensional description of the army
  unit composition of each human replay. The results demonstrate that the learned
  policy can be effectively manipulated to express distinct behaviors. Additionally,
  by applying the UCB1 algorithm, the policy can adapt its behavior - in-between games
  - to reach a performance beyond that of the traditional IL baseline approach.
publication: '*2020 IEEE Conference on Games*'
doi: 10.1109/CoG47356.2020.9231897
---
