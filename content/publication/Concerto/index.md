---
title: 'Concerto: Automatic Communication Optimization and Scheduling for Large-Scale Deep Learning'

# Authors
authors:
  - Shenggan Cheng
  - Shengjie Lin
  - Lansong Diao
  - Hao Wu
  - Siyu Wang
  - Chang Si
  - admin
  - Xuanlei Zhao
  - Jiangsu Du
  - Wei Lin
  - Yang You

date: '2025-03-30T00:00:00Z'  # Adjust the date as needed
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-30T00:00:00Z'  # Adjust the date as needed

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ASPLOS 2025
publication_short: To appear on ASPLOS 2025

abstract: With the exponential growth of deep learning (DL), there arises an escalating need for scalability. Despite significant advancements in communication hardware capabilities, the time consumed by communication processes remains a bottleneck during training. The existing various optimizations are coupled within parallel systems to implement specific computation-communication overlap. This approach poses challenges in terms of performance, programmability, and generality. In this paper, we introduce Concerto, a compiler framework designed to address these challenges by automatically optimizing and scheduling communication. We formulate the scheduling problem as a resource constrained project scheduling problem and use off-the-shelf solver to get the near-optimal scheduling. And use auto-decomposition to create overlap opportunity for critical (synchronous) communication. Our evaluation shows Concerto can match or outperform state-of-the-art parallel frameworks, including Megatron-LM, DeepSpeed, and Alpa, all of which include extensive hand-crafted communication optimization. Unlike previous works, Concerto decouples the parallel approach and communication optimization, then can generalize to a wide variety of parallelisms without manual optimization.

# Summary. An optional shortened abstract.
summary: A compiler framework designed to address these challenges by automatically optimizing and scheduling communication

tags:
  - Deep Learning Compiler
  - Communication Scheduling
  - High Performance Computing

# Display this page in the Featured widget?
featured: false

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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
