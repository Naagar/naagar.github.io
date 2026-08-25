---
title: "FInC Flow: Fast and Invertible k × k Convolutions for Normalizing Flows"
authors:
  - Aditya Kallappa
  - admin
  - Girish Varma
date: "2023-02-19T00:00:00Z"
publishDate: "2023-02-19T00:00:00Z"
doi: "10.5220/0011876600003417"
publication_types:
  - "paper-conference"
publication: "In *Proceedings of the 18th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2023) - Volume 5: VISAPP*, pp. 338–348"
publication_short: "18th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2023) – VISAPP"
abstract: "Invertible convolutions have been an essential element for building expressive normalizing flow-based generative models since their introduction in Glow. Several attempts have been made to design invertible k × k convolutions that are efficient in training and sampling passes. Though these attempts have improved the expressivity and sampling efficiency, they severely lagged behind Glow which used only 1 × 1 convolutions in terms of sampling time. Also, many of the approaches mask a large number of parameters of the underlying convolution, resulting in lower expressivity on a fixed run-time budget. We propose a k × k convolutional layer and Deep Normalizing Flow architecture which (i) has a fast parallel inversion algorithm with running time O(n k^2) (n is height and width of the input image and k is kernel size), (ii) masks the minimal amount of learnable parameters in a layer, and (iii) gives better forward pass and sampling times comparable to other k × k convolution-based models on real-world benchmarks."
summary: "Fast parallel inversion of k×k convolutions for efficient normalizing flows."
tags:
  - Normalizing Flow models
featured: true
links:
  - name: "arXiv"
    url: "https://arxiv.org/abs/2301.09266"
url_pdf: "https://arxiv.org/pdf/2301.09266.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: "https://naagar.github.io/FInC-Flow/"
url_slides: ""
url_source: "https://www.scitepress.org/Papers/2023/118766/118766.pdf"
url_video: ""
projects: []
---
