---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'   # default section spacing

sections:
  - block: resume-biography-3
  content:
    username: admin
    button:
      text: Download CV
      url: uploads/resume.pdf
    title: "Expertise"
    text: |-
      I am a mathematics education professor at Texas State University...
  design:
    css_class: hbx-bg-gradient
    avatar:
      size: medium
      shape: circle

  - block: markdown
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders: ['publications']
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders: ['publications']
        exclude_featured: false
    design:
      view: citation

  
---
