---
title: 'WeiPipe: Weight Pipeline Parallelism for Communication-Effective Long-Context Large Model Training'

# Authors
authors:
  - Junfeng Lin*
  - admin2
  - Yang You
  - Jun Wang
  - Weihao Zhang
  - Rong Zhao

author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - ""
  - ""
  - ""
  - ""

date: '2024-11-10T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-10T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: PPoPP 2025
publication_short: PPoPP 2025. \*:Equal Contribution

abstract: Training large language models (LLMs) has become increasingly expensive due to the rapid expansion in model size. Pipeline Parallelism is a widely used distributed training technique. However, as LLMs with larger context become prevalent and memory optimization techniques advance, traditional PP methods encounter greater communication challenges due to the increased size activations and gradients of activations. To address this issue, we introduce weight-pipeline parallelism (WeiPipe) that transitions from an activation-passing pipeline to a weight-passing pipeline. WeiPipe reduces communication costs and achieves more balanced utilization by transmitting only weights and their gradients between workers in a pipelined manner. WeiPipe does not rely on collective communication primitives, thus ensuring scalability. We present four variations of WeiPipe parallelism, including WeiPipe-Interleave, which emphasizes communication efficiency, and WeiPipe-Zero-Bubble, discussing the potential for minimal bubble ratios. Our implementation of WeiPipe-Interleave, performed on up to 32 GPUs and tested in large-context LLM training, demonstrates up to a 30.9% improvement in throughput with NVLink connections and an 82% improvement with PCIe and IB connections compared to state-of-the-art pipeline parallelism. Additionally, WeiPipe shows greater strong scalability compared to Fully Sharded Data Parallelism.

# Summary. An optional shortened abstract.
summary: PPoPP '25. A novel pipeline parallelism that communicate model weight rather than activation under long-sequence scenarios.

tags:
  - Pipeline Parallelism
  - Long Sequence Training
  - High Performance Computing

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
  caption: 'WeiPipe-Zero-Bubble'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
