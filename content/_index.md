---
title: ''
date: 2025-01-01
type: landing
design:
  spacing: '5rem'
sections:

  # HERO: bio + tight evaluation pitch

  - block: resume-biography-3
    content:
      username: admin
      text: |
        I am a **mathematics education professor at Texas State University**.  
        I work at the intersection of **measurement**, **instrument validation**, and **advanced quantitative methods**—supporting projects with right-sized, credible **external evaluation**.
      button:
        text: Download CV
        url: /uploads/resume.pdf

       text: | Expertise: **validity/modern test theory**, **HLM/GLM** for intervention efficacy, **fidelity of implementation**, **design-based research** in proof courses, and **computational methods** (classification, clustering, NLP).
      button:
        text: Talk to me about NSF External Evaluation Options 
        url: /evaluation/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle
    

  # RESEARCH BLURB (short)
  - block: markdown
    content:
      title: 'Research'
      text: |-
        I study **proof, language, and instructional practice** in undergraduate mathematics, alongside **instrument development & validation**.  
        Representative venues: *ESM, JRME, JMB*.
    design:
      columns: '1'

  # FEATURED PUBS
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders: [publications]
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # RECENT PUBS
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders: [publications]
        exclude_featured: false
    design:
      view: citation

  # GRANTS
  - block: markdown
    content:
      title: 'Grant Projects'
      text: |-
        - **NSF CORE** — External evaluator for research on proof and reasoning  
        - **RUME / EHR initiatives** — Quantitative reasoning & proof-language frameworks  
        - **Validation initiatives** — Synthesis and argument-based validity for instruments  
        - **PD efficacy studies** — HLM/GLM with design-sensitive summaries
      # Keep this short; link to a fuller page later if desired.
    design:
      columns: '1'

  # CTA
  - block: cta-card
    content:
      title: 'Let’s scope your evaluation'
      text: |-
        I build **utilization-focused** evaluation plans and reports aligned to **NSF/IES** expectations—grounded in strong measurement and modern quantitative methods.
      button:
        text: Request a consultation
        url: /contact/
    design:
      card:
        css_class: 'bg-primary-300'
---
