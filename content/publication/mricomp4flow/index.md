---
title: "MRIComp4Flow: Compression of 3D Brain MRI for Training Multi-Modal Generative Models"
authors:
  - Lisa K. Fischer
  - Mykhailo Riabets
  - Daniel Rueckert
  - Benedikt Wiestler
  - Anke Meyer-Baese
  - admin
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - ""
  - ""
  - ""
  - "Equal contribution"
date: "2026-08-10T00:00:00Z"
publishDate: "2026-08-10T00:00:00Z"
doi: ""
publication_types:
  - "article"
publication: "Preprint"
publication_short: "arXiv preprint"
abstract: "Large-scale multi-modal MRI datasets impose substantial storage and I/O costs, limiting the training of 3D generative models on commodity infrastructure. While lossy compression is known to preserve accuracy for discriminative segmentation networks, its effect on generative models, which must learn the full data distribution rather than a decision boundary, is unexplored. We study whether standard image codecs can effectively compress semantically rich brain tumor MRI while preserving the fidelity required to train and deploy a 3D MRI generative model. Each 3D volume is compressed with JPEG2000 or a near-lossless JPEG-LS pipeline. Next, a Wavelet Flow Matching model, conditioned on BraTS image sequences (T1n, T1c, T2, T2f), is trained on compressed data. At a 20:1 compression ratio, synthesis quality is statistically equivalent to a model trained on uncompressed data. Our results indicate that JPEG2000 compression is a practical step toward scalable 3D MRI generative modeling without degrading synthesis quality."
summary: "JPEG2000 compression of 3D brain MRI for training multi-modal generative flow-matching models."
tags:
  - Medical Imaging
  - Generative Models
  - MRI
featured: true
url_pdf: "https://arxiv.org/pdf/2608.10291.pdf"
url_code: "https://github.com/lisafis/MRIComp4Flow"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: "https://arxiv.org/abs/2608.10291"
url_video: ""
projects: []
---
