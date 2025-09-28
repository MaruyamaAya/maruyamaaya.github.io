---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_ZimingLiu_open_version.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Recent News'
      subtitle: ''
      text: |-

        <style>
        .news-item {
          margin: 0.2em 0;
          line-height: 1.2;
        }
        </style>

        <p class="news-item"><font size='3'>2025.09.22 We release Expert-as-a-Service (EaaS) for MoE serving!</font></p>

        <p class="news-item"><font size='3'>2025.09.18  One paper accepted by NeurIPS '25.</font></p>

        <p class="news-item"><font size='3'>2025.1 Joined Qiji Zhifeng as a research intern.</font></p>

        <p class="news-item"><font size='3'>2024.12.09  Release RAS for efficient DiTs. Code & paper: aka.ms/ras-dit</font></p>

        <p class="news-item"><font size='3'>2024.12.09  Awarded the "Stars of Tomorrow" Certificate from MSRA (top 10% intern).</font></p>

        <p class="news-item"><font size='3'>2024.11.12  One paper accepted by PPoPP 2025.</font></p>

        <p class="news-item"><font size='3'>2024.10.03  One paper accepted by ASPLOS '25.</font></p>

        <p class="news-item"><font size='3'>2024.06.27  Awarded the SoC Teaching Fellowship (3 out of all NUS CS PhD).</font></p>

        <p class="news-item"><font size='3'>2024.04.30  Joined Microsoft Research as a research intern.</font></p>

        <p class="news-item"><font size='3'>2024.02.16  One paper accepted by MLSYS 2024.</font></p>

        <p class="news-item"><font size='3'>2024.01.15  One paper accepted by ICLR '24.</font></p>

        <p class="news-item"><font size='3'>2023.06.17  One paper accepted by SC '23.</font></p>

        <p class="news-item"><font size='3'>2023.01.07  Started my PhD career.</font></p>

    design:
      columns: '1'
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many experience `items` below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Research Intern
  #         company: Microsoft Research
  #         company_url: https://www.msra.cn/zh-cn/msr-asia-shanghai
  #         company_logo: Microsoft_logo
  #         location: Shanghai
  #         date_start: '2024-05-01'
  #         date_end: ''
  #         description: |2-
  #             Working on sparse inference and training of text-to-image and text-to-video models. Supervised by Dr. Zhenhua Han and Dr. Yuqing Yang.
  #       - title: Research Intern
  #         company: HPC-AI Tech
  #         company_url: https://colossalai.org/
  #         company_logo: luchen
  #         location: Singapore
  #         date_start: '2022-05-01'
  #         date_end: '2022-12-01'
  #         description: |
  #             Responsibilities include:
  #             - Developing the efficient LLM inference system EnergonAI.
  #             - Optimizing the implementation of ColossalAI.
  #       - title: Machine Learning Engineer
  #         company: ByteDance
  #         company_url: https://www.bytedance.com/en/
  #         company_logo: bytedance
  #         location: Beijing
  #         date_start: '2020-09-01'
  #         date_end: '2021-06-01'
  #         description: |
  #             NLP algorithm engineer at Lark, ByteDance.
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 100
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
