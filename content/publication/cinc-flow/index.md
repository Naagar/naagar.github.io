---
title: "CInC Flow: Characterizable Invertible 3×3 Convolution"
authors:
  - admin
  - Marius Dufraisse
  - Girish Varma
date: "2021-07-03T00:00:00Z"
publishDate: "2021-07-03T00:00:00Z"
doi: ""
publication_types:
  - "paper-conference"
publication: "In *4th Workshop on Tractable Probabilistic Modeling*, Conference on Uncertainty in Artificial Intelligence (UAI 2021)"
publication_short: "4th Workshop on Tractable Probabilistic Modeling, Conference on Uncertainty in Artificial Intelligence (UAI 2021)"
abstract: "Normalizing flows are an essential alternative to GANs for generative modelling, which can be optimized directly on the maximum likelihood of the dataset. They also allow computation of the exact latent vector corresponding to an image since they are composed of invertible transformations. However, the requirement of invertibility of the transformation prevents standard and expressive neural network models such as CNNs from being directly used. Emergent convolutions were proposed to construct an invertible 3×3 CNN layer using a pair of masked CNN layers, making them inefficient. We study conditions such that 3×3 CNNs are invertible, allowing them to construct expressive normalizing flows. We derive necessary and sufficient conditions on a padded CNN for it to be invertible. Our conditions for invertibility are simple and can easily be maintained during the training process. Since we require only a single CNN layer for every effective invertible CNN layer, our approach is more efficient than emerging convolutions. We also proposed a coupling method, Quad-coupling. We benchmark our approach and show similar performance results to emergent convolutions while improving the model's efficiency."
summary: "Necessary and sufficient invertibility conditions for 3×3 convolutions in normalizing flows."
tags:
  - Normalizing Flow models
featured: true
links:
  - name: "OpenReview"
    url: "https://openreview.net/forum?id=kl1ds_AeLRM"
url_pdf: "https://arxiv.org/pdf/2107.01358.pdf"
url_code: "https://github.com/Naagar/Normalizing_Flow_3x3_inv"
url_dataset: ""
url_poster: ""
url_project: "https://naagar.github.io/CInCFlow/"
url_slides: ""
url_source: "https://arxiv.org/abs/2107.01358"
url_video: ""
projects: []
---
