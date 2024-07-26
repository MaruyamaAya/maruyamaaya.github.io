---
title: 'AutoChunk: Automated Activation Chunk for Memory-Efficient Long Sequence Inference'

# Authors
authors:
  - Xuanlei Zhao
  - Shenggan Cheng
  - Guangyang Lu
  - Jiarui Fang
  - Haotian Zhou
  - Bin Jia
  - admin
  - Yang You

date: '2024-05-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-07T00:00:00Z'

# Publication type.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: In *ICLR 2024, International Conference on Learning Representations*
publication_short: In *ICLR 2024, International Conference on Learning Representations*

abstract: Large deep learning models have achieved impressive performance across a range of applications. However, their large memory requirements, including parameter memory and activation memory, have become a significant challenge for their practical serving. While existing methods mainly address parameter memory, the importance of activation memory has been overlooked. Especially for long input sequences, activation memory is expected to experience a significant exponential growth as the length of sequences increases. In this approach, we propose AutoChunk, an automatic and adaptive compiler system that efficiently reduces activation memory for long sequence inference by chunk strategies. The proposed system generates chunk plans by optimizing through multiple stages. In each stage, the chunk search pass explores all possible chunk candidates and the chunk selection pass identifies the optimal one. At runtime, AutoChunk employs code generation to automatically apply chunk strategies. The experiments demonstrate that AutoChunk can reduce over 80\% of activation memory while maintaining speed loss within 10%, extend max sequence length by 3.2x to 11.7x, and outperform state-of-the-art methods by a large margin.

# Summary. An optional shortened abstract.
summary: Memory-efficient long sequence inference through automated activation chunking.

tags:
  - Memory-Efficient Inference
  - Long Sequence Inference
  - Activation Chunking

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/abs/2401.10652'
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
