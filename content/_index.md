---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        - **Sep 2026** — **GVCC** was accepted to **NeurIPS 2026**. [[arXiv]](https://arxiv.org/abs/2603.26571)
        - **Sep 2026** — Started the Ph.D. program at Katto Laboratory, Waseda University.
        - **Aug 2026** — **GVCCTurbo** is out on arXiv. [[arXiv]](https://arxiv.org/abs/2608.03517)
        - **Aug 2026** — A co-authored paper received the **MIRU 2026 Interactive Presentation Award**.
        - **Jun 2026** — Joined the CG Lab of Huawei Tokyo Da Vinci Research Institute as a Research Intern.
        - **Mar 2026** — **FRS** was published at IEVC 2026.
        - **Dec 2025** — **TSG** was presented as an oral paper at **ACM MMAsia 2025**.
        - **Sep 2025** — **Bi-AGMI** received the **Oral Presentation Award** at IEEE GCCE 2025.
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: Selected first-author papers.
      # Show all featured publications (0 = all)
      count: 0
      filters:
        folders:
          - publication
        featured_only: true
      archive:
        enable: true
        text: All publications
        link: publication/
    design:
      columns: '2'
      view: citation

  - block: portfolio
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - project
      # Order projects by the `weight` set in each project's front matter.
      sort_by: Weight
      sort_ascending: true
    design:
      columns: '2'
      view: compact

  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Ph.D. Student (Katto Laboratory)
          company: Waseda University
          company_url: 'https://www.waseda.jp/'
          company_logo: ''
          location: Tokyo, Japan
          date_start: '2026-09-01'
          date_end: ''
          description: |2-
              * Research on generative compression and compressed representation understanding
        - title: Research Intern (CG Lab)
          company: Huawei Tokyo Da Vinci Research Institute
          company_url: 'https://www.huawei.com/jp/'
          company_logo: ''
          location: Tokyo, Japan
          date_start: '2026-06-01'
          date_end: ''
          description: ''
        - title: Research Assistant
          company: National Institute of Information and Communications Technology (NICT)
          company_url: 'https://www.nict.go.jp/'
          company_logo: ''
          location: Tokyo, Japan
          date_start: '2025-04-01'
          date_end: '2026-04-01'
          description: |2-
              * Applied diffusion-based frame interpolation to video compression and transmission
              * Proposed **Bi-AGMI**, bidirectional attention-gated keyframe interpolation with diffusion models (IEEE GCCE 2025, Oral Presentation Award)
              * Proposed **FRS**, motion-aware video segmentation for generative video coding (IEVC 2026)
        - title: Master's Student (Watanabe Laboratory)
          company: Waseda University
          company_url: 'https://www.waseda.jp/'
          company_logo: ''
          location: Tokyo, Japan
          date_start: '2024-09-01'
          date_end: '2026-07-01'
          description: |2-
              * Proposed **GVCC**, zero-shot video compression with a pretrained video generative model as the decoder (NeurIPS 2026), and its rate–compute scheduler **GVCCTurbo**
              * Proposed **TSG**, a universal synthesized image detector built on pretrained diffusion features (ACM MMAsia 2025, Oral)
              * Co-authored five papers on scalable image and video coding for humans and machines
              * Collaborated on large-motion frame interpolation with Stable Video Diffusion and ControlNet
        - title: Research Assistant
          company: Chongqing University – Information Processing Lab
          company_url: 'https://www.cqu.edu.cn/'
          company_logo: ''
          location: Chongqing, China
          date_start: '2021-09-01'
          date_end: '2024-06-01'
          description: |2-
              * Research on evidence theory and information fusion
              * Two first-author journal articles (*Chaos, Solitons & Fractals*; *Computational and Applied Mathematics*)
    design:
      columns: '2'

  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: Feel free to reach out by email about research or collaboration.
      email: zengziyue@fuji.waseda.jp
      address:
        street: 3-4-1 Okubo, Shinjuku
        city: Tokyo
        postcode: '169-8555'
        country: Japan
        country_code: JPN
      # Shown on a map (provider set in `params.yaml`)
      coordinates:
        latitude: '35.7090'
        longitude: '139.7195'
      # Automatically link email and phone or display as text?
      autolink: true
      # No contact form: GitHub Pages cannot receive form submissions
      form:
        provider: ''
    design:
      columns: '2'
---
