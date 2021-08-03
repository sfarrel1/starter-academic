---
title: Can Theoretical Algorithms Efficiently Escape Saddle Points in Deep Learing?
summary: Literary review and experimental evaluation of non-convex optimization functions designed to escape saddle points in Deep Learning.
tags:
- Optimization
- Deep Learning
date: "2021-08-3T00:00:00Z"
authors:
- admin
- carlos
# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Saddle point affecting gradient descent
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "pdfs/Escaping_Saddle_Points.pdf"
url_slides: "slides/optimization/EscapingSaddlePoints_CompleteFV.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

This document provides a literature review for the most important recent works related to opti- mizing high-dimensional non-convex functions in the presence of saddle points mostly for machine learning applications. 

The inspiration came from reviewing the paper ”How to Escape Saddle Points Efficiently?” (Jin et al., 2017a). A large research effort has been devoted to proposed methods that can converge to second order stationary points efficiently. Of special interest is the set of methods that do not rely on Hessian computation, mainly driven by applications in machine learn- ing where this may not be feasible. Although, many important theoretical results have been pro- posed, many of them have not be tested in real experiments, especially in the context of training a deep neural network. We have designed experiments with different network architectures and state-of-the-art datasets to observe the behavior of perturbed versions of gradient descent. Initial results show that an improvement in experimental convergence rate can be seen only for small and shallow networks.
