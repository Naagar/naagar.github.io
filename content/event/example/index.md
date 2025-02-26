---
title: Inverse-Flow

event: AISTATS'25
event_url: https://aistats.org/aistats2025/

location: Splash Beach Resort
address:
  street: 65 4894+7PV
  city: Mai Khao
  region: Phuket
  postcode: '83110'
  country: Thailand

summary: Parallel Backpropagation for Inverse of a Convolution with Application to Normalizing Flows.
abstract: 'The inverse of an invertible convolution is an important operation that comes up in Normalizing Flows, Image Deblurring, etc. The naive algorithm for backpropagation of this operation using Gaussian elimination has running time O(n3) where n is the number of pixels in the image. We give a fast parallel backpropagation algorithm with running time O(√n) for a square image and provide a GPU implementation of the same. Inverse of Convolutions are usually used in Normalizing Flows in the sampling pass, making them slow. We propose to use the Inverse of Convolutions in the forward (image to latent vector) pass of the Normalizing flow. Since the sampling pass is the inverse of the forward pass, it will use convolutions only, resulting in efficient sampling times. We use our parallel backpropagation algorithm for optimizing the inverse of convolution layer resulting in fast training times also. We implement this approach in various Normalizing Flow backbones, resulting in our Inverse- Flow models. We benchmark Inverse-Flow on standard datasets and show significantly improved sampling times with similar bits per dimension compared to previous models.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-03T13:00:00Z'
date_end: '2025-05-04T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-01-21T00:00:00Z'

authors:
  - Sandeep Nagar

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_InverseFlow/static/images/multiScale_if_flow.jpg)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/girish-lab/Inverse-Flow'
url_pdf: 'https://arxiv.org/pdf/2410.14634.pdf'
url_slides: 'https://naagar.github.io/projectPage_InverseFlow/'
url_video: 'https://naagar.github.io/projectPage_InverseFlow/'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Inverse-Flow
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
