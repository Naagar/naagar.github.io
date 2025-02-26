---
title: "Remote Sensing Framework for Geological Mapping via Stacked Autoencoders and Clustering"
authors:
- Sandeep Nagar*
- Ehsan Farahbakhsh*
- Joseph Awange
- Rohitash Chandra
author_notes:
- "Equal contribution"
date: "2024-04-02T00:00:00Z"
doi: "https://doi.org/10.1016/j.asr.2024.09.013"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Advances in Space Research Journal, 74*(10)"
publication_short: "ASR"

abstract: Supervised machine learning methods for geological mapping via remote sensing face limitations due to the scarcity of accurately labelled training data that can be addressed by unsupervised learning, such as dimensionality reduction and clustering. Dimensionality reduction methods have the potential to play a crucial role in improving the accuracy of geological maps. Although conventional dimensionality reduction methods may struggle with nonlinear data, unsupervised deep learning models such as autoencoders can model non-linear relationships. Stacked autoencoders feature multiple interconnected layers to capture hierarchical data representations useful for remote sensing data. We present an unsupervised machine learning-based framework for processing remote sensing data using stacked autoencoders for dimensionality reduction and k-means clustering for mapping geological units. We use Landsat 8, ASTER, and Sentinel-2 datasets to evaluate the framework for geological mapping of the Mutawintji region in Western New South Wales, Australia. We also compare stacked autoencoders with principal component analysis (PCA) and canonical autoencoders. Our results reveal that the framework produces accurate and interpretable geological maps, efficiently discriminating rock units. The results reveal that the combination of stacked autoencoders with Sentinel-2 data yields the best performance accuracy when compared to other combinations. We find that stacked autoencoders enable better extraction of complex and hierarchical representation of the input data when compared to canonical autoencoders and PCA. We also find that the generated maps align with prior geological knowledge of the study area while providing novel insights into geological structures.

# Summary. An optional shortened abstract.
summary: Keywords-- Remote Sensing, Deep Learning, Dimensionality Reduction, Stacked Autoencoders, k-means Clustering, Geological Mapping

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0273117724009335/pdfft?md5=81f96f9b1386d6728b3efb08de65dc1b&pid=1-s2.0-S0273117724009335-main.pdf
url_code: 'https://github.com/sydney-machine-learning/autoencoders_remotesensing'
url_dataset: ''
url_poster: ''
url_project: 'https://naagar.github.io/project_page_stackedAE4Geo/'
url_slides: 'https://naagar.github.io/project_page_stackedAE4Geo/'
url_source: 'https://www.sciencedirect.com/science/article/pii/S0273117724009335'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: [here](https://naagar.github.io/project_page_stackedAE4Geo/)
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
