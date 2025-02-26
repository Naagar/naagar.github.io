---
title: 'Inverse-Flow: Parallel Backpropagation for Inverse of a Convolution with Application to Normalizing Flows'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sandeep Nagar
  - Girish Varma

# Author notes (optional)
author_notes:
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'

date: '2025-01-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Artificial Intelligence and Statistics*
publication_short: In *AISTATS*

abstract: The inverse of an invertible convolution is an important operation that comes up in Normalizing Flows, Image Deblurring, etc. The naive algorithm for backpropagation of this operation using Gaussian elimination has running time O(n^3) where n is the number of pixels in the image. We give a fast parallel backpropagation algorithm with running time O(√n) for a square image and provide a GPU implementation of the same. Inverse of Convolutions are usually used in Normalizing Flows in the sampling pass, making them slow. We propose to use the Inverse of Convolutions in the forward (image to latent vector) pass of the Normalizing flow. Since the sampling pass is the inverse of the forward pass, it will use convolutions only, resulting in efficient sampling times. We use our parallel backpropagation algorithm for optimizing the inverse of convolution layer resulting in fast training times also. We implement this approach in various Normalizing Flow backbones, resulting in our Inverse- Flow models. We benchmark Inverse-Flow on standard datasets and show significantly improved sampling times with similar bits per dimension compared to previous models.

# Summary. An optional shortened abstract.
summary: Backpropogation Algorithm for the Fanst and Effecient Inverse of Convolution and Inverse-Flow model.

tags:
  - Normalizing Flow models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.14634.pdf'
url_code: 'https://github.com/girish-lab/Inverse-Flow'
url_dataset: 'https://github.com/girish-lab/Inverse-Flow'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2410.14634'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_InverseFlow/static/images/multiScale_if_flow.jpg)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Inverse-Flow

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: [here](https://naagar.github.io/projectPage_InverseFlow/)
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
