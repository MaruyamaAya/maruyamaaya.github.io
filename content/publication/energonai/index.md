---
title: 'EnergonAI: An Inference System for 10-100 Billion Parameter Transformer Models'

# Authors
authors:
  - Jiangsu Du
  - admin
  - Jiarui Fang
  - Shenggui Li
  - Yongbin Li
  - Yutong Lu
  - Yang You

date: '2022-01-01T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: Large transformer models display promising performance on a wide range of natural language processing (NLP) tasks. Although the AI community has expanded the model scale to the trillion parameter level, the practical deployment of 10-100 billion parameter models is still uncertain due to the latency, throughput, and memory constraints.
In this paper, we proposed EnergonAI to solve the challenges of the efficient deployment of 10-100 billion parameter transformer models on single- or multi-GPU systems. EnergonAI adopts a hierarchy-controller system architecture to coordinate multiple devices and efficiently support different parallel patterns. It delegates the execution of sub-models to multiple workers in the single-controller style and applies tensor parallelism and pipeline parallelism among the workers in a multi-controller style. Upon the novel architecture, we propose three techniques, i.e. non-blocking pipeline parallelism, distributed redundant computation elimination, and peer memory pooling. EnergonAI enables the users to program complex parallel code the same as a serial one. Compared with the FasterTransformer, we have proven that EnergonAI has superior performance on latency and throughput. In our experiments, EnergonAI can achieve 37% latency reduction in tensor parallelism, 10% scalability improvement in pipeline parallelism, and it improves the model scale inferred on a single GPU by using a larger heterogeneous memory space at cost of limited performance reduction.

# Summary. An optional shortened abstract.
summary: An inference system designed for handling 10-100 billion parameter transformer models efficiently.

tags:
  - Inference Systems
  - Transformer Models
  - Large Scale AI

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2209.02341'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/hpcaitech/EnergonAI'
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
