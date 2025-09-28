---
title: 'Expert-as-a-Service: Towards Efficient, Scalable, and Robust Large-scale MoE Serving'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Boyu Tian
  - Guoteng Wang
  - Zhen Jiang
  - Peng Sun
  - Zhenhua Han
  - Tian Tang
  - Xiaohe Hu
  - Yanmin Jia
  - Yan Zhang
  - He Liu
  - Mingjun Zhang
  - Yiqi Zhang
  - Qiaoling Chen
  - Shenggan Cheng
  - Mingyu Gao
  - Yang You
  - Siyuan Feng

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: Mixture-of-Experts (MoE) models challenge serving infrastructures with dynamic, sparse expert utilization, causing instability on conventional systems designed for dense architectures. We propose EaaS, a novel serving system to enable efficient, scalable, and robust MoE deployment. Our system disaggregates MoE modules into independent, stateless services. This design enables fine-grained resource scaling and provides inherent fault tolerance by decoupling compute units. The architecture is powered by a high-performance, CPU-free peer-to-peer communication library that ensures minimal overhead and high throughput. Experiments confirm EaaS's scalability and efficiency, achieving performance comparable to monolithic systems while providing robust fault tolerance and strong scalability. EaaS incurs less than a 2% throughput reduction under simulated hardware failures that would otherwise halt monolithic architectures. It further saves up to 37.5% of computing resources through dynamic fine-grained adaptation to serving traffic, demonstrating strong resilience for large-scale MoE deployment in production.

# Summary. An optional shortened abstract.
summary: EaaS, a novel serving system to enable efficient, scalable, and robust MoE deployment.

tags:
  - Mixture-of-Experts
  - Distributed Serving
  - Elastic Serving

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2509.17863'
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
  caption: 'EaaS Design'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: 
  #  - RAS

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
