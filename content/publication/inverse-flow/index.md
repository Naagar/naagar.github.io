---
title: "Inverse-Flow: Parallel Backpropagation for Inverse of a Convolution with Application to Normalizing Flows"
authors:
  - admin
  - Girish Varma
author_notes:
  - "Machine Learning Lab, IIIT-Hyderabad"
  - "Machine Learning Lab, IIIT-Hyderabad"
date: "2025-05-03T00:00:00Z"
publishDate: "2025-05-03T00:00:00Z"
doi: ""
publication_types:
  - "paper-conference"
publication: "In *Proceedings of The 28th International Conference on Artificial Intelligence and Statistics* (PMLR 258:3313–3321)"
publication_short: "The 28th International Conference on Artificial Intelligence and Statistics (AISTATS 2025)"
abstract: "The inverse of an invertible convolution is an important operation that comes up in Normalizing Flows, Image Deblurring, etc. The naive algorithm for backpropagation of this operation using Gaussian elimination has running time O(n^3) where n is the number of pixels in the image. We give a fast parallel backpropagation algorithm with running time O(√n) for a square image and provide a GPU implementation of the same. Inverse of Convolutions are usually used in Normalizing Flows in the sampling pass, making them slow. We propose to use the Inverse of Convolutions in the forward (image to latent vector) pass of the Normalizing flow. Since the sampling pass is the inverse of the forward pass, it will use convolutions only, resulting in efficient sampling times. We use our parallel backpropagation algorithm for optimizing the inverse of convolution layer resulting in fast training times also. We implement this approach in various Normalizing Flow backbones, resulting in our Inverse-Flow models. We benchmark Inverse-Flow on standard datasets and show significantly improved sampling times with similar bits per dimension compared to previous models."
summary: "Fast parallel backpropagation for inverse of convolution, enabling Inverse-Flow normalizing flow models."
tags:
  - Normalizing Flow models
featured: true
aliases:
  - "/publication/conference-paper/"
links:
  - name: "arXiv"
    url: "https://arxiv.org/abs/2410.14634"
url_pdf: "https://arxiv.org/pdf/2410.14634.pdf"
url_code: "https://github.com/girish-lab/Inverse-Flow"
url_dataset: ""
url_poster: ""
url_project: "https://naagar.github.io/InverseFlow/"
url_slides: ""
url_source: "https://proceedings.mlr.press/v258/nagar25a.html"
url_video: ""
projects: []
---
