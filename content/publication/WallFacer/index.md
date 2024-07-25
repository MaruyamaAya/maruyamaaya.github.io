---
title: 'WallFacer: Guiding Transformer Model Training Out of the Long-Context Dark Forest with N-body Problem'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shaoyu Wang
  - Shenggan Cheng
  - Zhongkai Zhao
  - Xuanlei Zhao
  - Hames Demmel
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
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: In recent years, Transformer-based Large Language Models (LLMs) have garnered significant attention due to their exceptional performance across a variety of tasks. However, training these models on long sequences presents a substantial challenge in terms of efficiency and scalability. Current methods are constrained either by the number of attention heads, limiting scalability, or by excessive communication overheads. In this paper, we propose an insight that Attention Computation can be considered as a special case of n-body problem with direct interactions. Based on this concept, this paper introduces WallFacer, an efficient long-sequence training system with a novel multi-dimensional ring sequence parallelism, fostering an efficient communication paradigm and extra tuning space for communication arrangement. Through comprehensive experiments under diverse environments and model settings, we demonstrate that WallFacer significantly surpasses state-of-the-art method that supports near-infinite sequence length, achieving performance improvements of up to 77.12%.

# Summary. An optional shortened abstract.
summary: Efficient Sequence Parallelism System for Transformer model training.

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
  caption: 'WallFacer Attention Block'
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
