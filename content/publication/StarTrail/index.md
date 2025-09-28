---
title: 'StarTrail: Concentric Ring Sequence Parallelism for Efficient Near-Infinite-Context Transformer Model Training'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shaoyu Wang
  - Shenggan Cheng
  - Zhongkai Zhao
  - Kai Wang
  - Xuanlei Zhao
  - James Demmel
  - Yang You

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-06-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: NeurIPS 2025
publication_short: NeurIPS 2025

abstract: Training Transformer models on long sequences in a distributed setting poses significant challenges in terms of efficiency and scalability. Current methods are either constrained by the number of attention heads or excessive communication overheads. To address this problem, we propose StarTrail, a multi-dimensional concentric distributed training system for long sequences, fostering an efficient communication paradigm and providing additional tuning flexibility for communication arrangements. Specifically, StarTrail introduces an extra parallel dimension and divides the peer-to-peer communication into sub-rings to substantially reduce communication volume and avoid bandwidth bottlenecks. Through comprehensive experiments across diverse hardware environments and on both Natural Language Processing (NLP) and Computer Vision (CV) tasks, we demonstrate that our approach significantly surpasses state-of-the-art methods that support Long sequence lengths, achieving performance improvements of up to 77.12% on GPT-style models and up to 114.33% on DiT (Diffusion Transformer) models without affecting the computations results.

# Summary. An optional shortened abstract.
summary: NeurIPS '25. Efficient Sequence Parallelism System for Transformer model training.

tags:
  - Sequence Parallelism
  - Large Language Models
  - High Performance Computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2407.00611'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'StarTrail Attention Block'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#   - example

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
