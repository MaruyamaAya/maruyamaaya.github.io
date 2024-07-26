---
title: 'ATP: Adaptive Tensor Parallelism for Foundation Models'

# Authors
authors:
  - Shenggan Cheng
  - admin
  - Jiangsu Du
  - Yang You

date: '2023-01-01T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: Foundation models have impressive performance and generalization capabilities across a wide range of applications. The increasing size of the models introduces great challenges for the training. Tensor parallelism is a critical technique that is currently used in almost all foundation model training and has a significant impact on overall training performance. However, current tensor parallelism in machine learning frameworks misses optimization opportunities in fitting various interconnection topologies. In this work, we present ATP, an adaptive tensor parallelism framework for foundation models, which can automatically select the optimal parallel strategy on different interconnections. We propose column- and row-first tensor parallelism based on 2D device meshes and construct a search space. Combined with the hierarchical communication matrix, ATP can identify the optimal strategy in the search space. We also propose chunk-based overlapping to reduce communication overhead. Our evaluations show ATP consistently outperforms the state-of-the-art approaches for various model sizes and interconnects, achieving end-to-end training performance improvements of up to 37-64% on specific interconnects. Based on our theoretical model, the communication overhead of ATP decreases with scaling, indicating a qualitative leap forward.

# Summary. An optional shortened abstract.
summary: Adaptive Tensor Parallelism for efficient foundation model training.

tags:
  - Tensor Parallelism
  - Foundation Models
  - High Performance Computing

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/abs/2301.08658'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
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
