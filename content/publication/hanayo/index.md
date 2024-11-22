---
title: 'Hanayo: Harnessing Wave-like Pipeline Parallelism for Enhanced Large Model Training Efficiency'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin2
  - Shenggan Cheng*
  - Haotian Zhou
  - Yang You

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ""
  - ""

date: '2023-11-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *SC '23, Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis*
publication_short: In *SC '23, Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis*. \*:Equal Contribution.

abstract: Large-scale language models have become increasingly challenging and expensive to train. Among various methods addressing this issue, Pipeline Parallelism has been widely employed to accommodate massive model weights within limited GPU memory. This paper introduces Hanayo, a wave-like pipeline parallelism strategy that boasts a concise structure and practical applicability, alongside a high-performance pipeline execution runtime to tackle the challenges of pipeline strategy implementation. Hanayo mitigates the issues of pipeline bubbles and excessive memory consumption prevalent in existing schemes, without resorting to model duplicates as in Chimera. Our evaluation, conducted on four distinct computing clusters and involving both GPT-like and BERT-like architectures with up to 32 GPUs, demonstrates up to a 30.4 % increase in throughput compared to the state-of-the-art approach.

# Summary. An optional shortened abstract.
summary: Accepted by SC '23.  Efficient Pipeline Parallelism System for LLM.

tags:
  - Pipeline Parallelism
  - Large Language Models
  - High Performance Computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3581784.3607073'
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
  caption: 'Hanayo Pipeline Scheme'
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
