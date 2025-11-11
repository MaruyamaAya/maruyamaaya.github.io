---
title: 'HelixPipe: Efficient Distributed Training of Long Sequence Transformers with Attention Parallel Pipeline Parallelism'

# Authors
authors:
  - Geng Zhang
  - Shenggan Cheng
  - Xuanlei Zhao
  - Ziming Liu
  - Yang You

date: '2025-11-11T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-11T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: PPoPP 2026
publication_short: PPoPP 2026.

abstract: As transformer sequence lengths grow, existing pipeline parallelisms incur suboptimal performance due to the quadratic attention computation and the substantial memory overhead. To relieve these challenges, we propose HelixPipe, a novel pipeline parallelism for long sequence transformer training. First, HelixPipe introduces attention parallel partition, which schedules attention computations of different micro batches across different pipeline stages in parallel, reducing pipeline bubbles. Second, it employs a two-fold first-in-last-out micro batch schedule to balance memory usage and overlap communication with computation. Additionally, HelixPipe utilizes recomputation without attention and chunked MLP to mitigate fragmentation and enable longer sequences. Experiments demonstrate that HelixPipe gains increasing advantages with longer sequence lengths, and outperforms existing methods in throughput and scalability across varying pipeline sizes, model sizes, and cluster configurations. Notably, it achieves a 26\% speedup over baseline methods when training a 7B model with 128k sequence length on 64 H20 GPUs.

# Summary. An optional shortened abstract.
summary: PPoPP '26. A novel pipeline parallelism for long sequence transformer training.

tags:
  - Pipeline Parallelism
  - Long Sequence Training
  - High Performance Computing

# Display this page in the Featured widget?
featured: false

url_pdf: ''
url_code: 'https://github.com/code-tunnel/Megatron-LM/tree/dev'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
