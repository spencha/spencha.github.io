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
      buttons:
        - text: Download CV
          url: uploads/CV.pdf
        - text: Download Résumé
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
        My research develops statistical and machine learning methodology for valid inference and prediction on heterogeneous, multi-modal time series, with applications spanning mobile health, personalized medicine, and financial data. Current projects include:

        **Modality Disagreement in Multi-Modal Models** — Developing methodology to quantify disagreement across data modalities and to test its significance in modeling the output variable.

        **Selective Inference for Time-Varying Causal Effects** — Developing procedures that remain valid when models are chosen from the data, applied to identifying time-varying moderators of causal effects via the ordered lasso.
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
    id: mentorship
    content:
      title: 'Mentorship'
      subtitle: ''
      text: |-
        **Bryson Harris** (UC Santa Barbara) — Mentoring on financial time series modeling through weekly research meetings.

        **Daniel You** (UC Santa Barbara) — Mentoring on generative diffusion modeling with an application to soccer tactics through weekly research meetings.
    design:
      columns: '1'

  - block: markdown
    id: awards
    content:
      title: 'Awards & Fellowships'
      subtitle: ''
      text: |-
        **T32 STEER in Biomedical Sciences Fellow** (2025, renewed 2026) — NIH-funded training fellowship supporting research at the intersection of statistics and biomedical sciences, University of California, Irvine.

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
