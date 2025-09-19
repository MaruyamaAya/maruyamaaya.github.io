---
title: 'Region-Adaptive Sampling for Diffusion Transformers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yifan Yang
  - Chengruidong Zhang
  - Yiqi Zhang
  - Lili Qiu
  - Yang You
  - Yuqing Yang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: Diffusion models (DMs) have become the leading choice for generative tasks across diverse domains. However, their reliance on multiple sequential forward passes significantly limits real-time performance. Previous acceleration methods have primarily focused on reducing the number of sampling steps or reusing intermediate results, failing to leverage variations across spatial regions within the image due to the constraints of convolutional U-Net structures. By harnessing the flexibility of Diffusion Transformers (DiTs) in handling variable number of tokens, we introduce RAS, a novel, training-free sampling strategy that dynamically assigns different sampling ratios to regions within an image based on the focus of the DiT model. Our key observation is that during each sampling step, the model concentrates on semantically meaningful regions, and these areas of focus exhibit strong continuity across consecutive steps. Leveraging this insight, RAS updates only the regions currently in focus, while other regions are updated using cached noise from the previous step. The model's focus is determined based on the output from the preceding step, capitalizing on the temporal consistency we observed. We evaluate RAS on Stable Diffusion 3 and Lumina-Next-T2I, achieving speedups up to 2.36x and 2.51x, respectively, with minimal degradation in generation quality. Additionally, a user study reveals that RAS delivers comparable qualities under human evaluation while achieving a 1.6x speedup. Our approach makes a significant step towards more efficient diffusion transformers, enhancing their potential for real-time applications.

# Summary. An optional shortened abstract.
summary: RAS, the first diffusion sampling strategy that allows for regional variability in sampling ratios, achieving up to 2x+ speedup!

tags:
  - Diffusion Transformer
  - Diffusion Model
  - Sampling

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2502.10389'
url_code: 'https://github.com/microsoft/RAS'
url_dataset: ''
url_poster: 'https://microsoft.github.io/RAS/'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'RAS Design'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
   - RAS

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
