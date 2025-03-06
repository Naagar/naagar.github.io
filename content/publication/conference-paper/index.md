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
projects: []
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: [here](https://naagar.github.io/projectPage_InverseFlow/)
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->


<!-- ---
title: 'CIinC Flow: Characterizable Invertible 3×3 Convolution'

# Authors
authors:
  - Sandeep Nagar
  - Marius Dufraisse
  - Girish Varma

# Author notes (optional)
author_notes:
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'

date: '2021-05-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 4th Workshop on Tractable Probabilistic Modeling*
publication_short: In *TPM*

abstract: This paper introduces CIinC Flow, a novel approach for characterizable invertible 3×3 convolutions. The method is designed to improve the efficiency and performance of normalizing flows.

# Summary. An optional shortened abstract.
summary: Characterizable Invertible 3×3 Convolution for Normalizing Flows.

tags:
  - Normalizing Flow models

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://openreview.net/forum?id=kl1ds_AeLRM'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://openreview.net/forum?id=kl1ds_AeLRM'
url_video: ''

# Featured image
image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_InverseFlow/static/images/cinc_flow.jpg)'
  focal_point: ''
  preview_only: false

projects: []
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
--- 

title: 'FInC Flow: Fast and Invertible k × k Convolutions for Normalizing Flows'

# Authors
authors:
  - Aditya Kallappa
  - Sandeep Nagar
  - Girish Varma

# Author notes (optional)
author_notes:
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'

date: '2023-03-05T00:00:00Z'
doi: '10.5220/0011876600003417'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 18th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2023) - Volume 5: VISAPP*
publication_short: In *VISAPP*

abstract: This paper presents FInC Flow, a fast and invertible k × k convolution method for normalizing flows. The approach significantly improves the efficiency of normalizing flows by leveraging fast convolution techniques.

# Summary. An optional shortened abstract.
summary: Fast and Invertible k × k Convolutions for Normalizing Flows.

tags:
  - Normalizing Flow models

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_InverseFlow/static/images/finc_flow.jpg)'
  focal_point: ''
  preview_only: false

projects: []
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

---
title: 'Data anonymization in Indian Driving Dataset using Impanting'

# Authors
authors:
  - Sandeep Nagar
  - S. Puttagunta
  - Girish Varma

# Author notes (optional)
author_notes:
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'

date: '2024-05-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Preparation*
publication_short: In *Preparation*

abstract: This paper discusses data anonymization techniques in the Indian Driving Dataset using implanting methods.

# Summary. An optional shortened abstract.
summary: Data anonymization in Indian Driving Dataset using Impanting.

tags:
  - Data Anonymization
  - Driving Dataset

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_data_anonymization.jpg)'
  focal_point: ''
  preview_only: false

projects: []
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

---
title: 'Inverse of Convolution for Sparse Blind Deconvolution'

# Authors
authors:
  - Sandeep Nagar
  - Girish Varma

# Author notes (optional)
author_notes:
  - 'Machine Learning Lab, IIIT-Hyderabad'
  - 'Machine Learning Lab, IIIT-Hyderabad'

date: '2024-05-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Preparation*
publication_short: In *Preparation*

abstract: This paper discusses the inverse of convolution for sparse blind deconvolution.

# Summary. An optional shortened abstract.
summary: Inverse of Convolution for Sparse Blind Deconvolution.

tags:
  - Sparse Blind Deconvolution

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'Image credit: [**Unsplash**](https://naagar.github.io/projectPage_InverseFlow/static/images/sparse_blind_deconvolution.jpg)'
  focal_point: ''
  preview_only: false

projects: []
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->