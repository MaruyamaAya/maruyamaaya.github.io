---
title: 'DSP: Dynamic Sequence Parallelism for Multi-Dimensional Transformers'

# Authors
authors:
  - Xuanlei Zhao
  - Shenggan Cheng
  - Zangwei Zheng
  - Zheming Yang
  - admin
  - Yang You

date: '2024-01-01T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: Scaling multi-dimensional transformers to long sequences is indispensable across various domains. However, the challenges of large memory requirements and slow speeds of such sequences necessitate sequence parallelism. All existing approaches fall under the category of embedded sequence parallelism, which are limited to shard along a single sequence dimension, thereby introducing significant communication overhead. However, the nature of multi-dimensional transformers involves independent calculations across multiple sequence dimensions. To this end, we propose Dynamic Sequence Parallelism (DSP) as a novel abstraction of sequence parallelism. DSP dynamically switches the parallel dimension among all sequences according to the computation stage with efficient resharding strategy. DSP offers significant reductions in communication costs, adaptability across modules, and ease of implementation with minimal constraints. Experimental evaluations demonstrate DSP's superiority over state-of-the-art embedded sequence parallelism methods by remarkable throughput improvements ranging from 32.2% to 10x, with less than 25% communication volume.

# Summary. An optional shortened abstract.
summary: Dynamic Sequence Parallelism for multi-dimensional transformers.

tags:
  - Sequence Parallelism
  - Multi-Dimensional Transformers
  - High Performance Computing

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/abs/2403.10266'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/NUS-HPC-AI-Lab/OpenDiT'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
