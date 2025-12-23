---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on developing statistical methods for healthcare applications, particularly in the context of mobile health and personalized medicine. I am currently working on two main projects:

        **Causal Mediation Analysis for Type 1 Diabetes** — Developing autoencoder-based methods to understand how meal carbohydrate intake affects post-meal glucose trajectories through insulin bolusing behavior.

        **Tensor-Based Reinforcement Learning for Adaptive Insulin Dosing** — Building personalized treatment recommendation frameworks using tensor factorization methods for longitudinal continuous glucose monitoring data.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation

  - block: collection
    id: presentations
    content:
      title: Presentations
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: card

  - block: markdown
    id: awards
    content:
      title: 'Awards & Fellowships'
      subtitle: ''
      text: |-
        **T32 STEER in Biomedical Sciences Fellow** (2025) — NIH-funded training fellowship supporting research at the intersection of statistics and biomedical sciences, University of California, Irvine.

        **Diversity Recruitment Fellowship** (2023) — Fellowship awarded to support doctoral studies in Statistics at the University of California, Irvine.

        **PREDOC Summer Program** (2022) — Selected for competitive data analytics training program at Harvard University's Opportunity Insights, directed by economists Raj Chetty, John Friedman, and Nathaniel Hendren.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        Feel free to reach out via email at [shilligo@uci.edu](mailto:shilligo@uci.edu).

        **Office**: Department of Statistics, University of California, Irvine
    design:
      columns: '1'
---
