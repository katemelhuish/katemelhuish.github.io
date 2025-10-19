---
title: "Experience"
date: 2023-10-24
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-experience
    content:
      title: Professional Experience
      items:
        - company: Texas State University
          company_url: https://www.txst.edu/
          location: San Marcos, TX
          positions:
            - title: Professor of Mathematics Education
              date_start: 2020-08-01
              date_end: ""
              description: |-
                - Lead research in measurement (CTT/IRT), instrument validation, and proof-focused DBR.
                - Supervise graduate students; PI/co-PI on NSF projects.
        # Add more employers as needed:
        # - company: Prior University
        #   location: City, ST
        #   positions:
        #     - title: Associate Professor
        #       date_start: 2016-08-01
        #       date_end: 2020-07-31
        #       description: |-
        #         - Bullet 1
        #         - Bullet 2
    design:
      date_format: "January 2006"
      is_education_first: false

  - block: resume-skills
    content:
      title: Skills & Hobbies
      items:
        - name: Measurement & IRT
          description: "CTT, Rasch, 2PL/3PL, DIF, Wright maps"
          percent: 100
        - name: Quant Methods
          description: "GLM, HLM, SEM; R (tidyverse, lme4, mirt)"
          percent: 100
        - name: NLP / ML
          description: "spaCy, Transformers, weak supervision"
          percent: 90
        - name: Hobbies
          description: "Trail running, garden design, dog wrangling"
          percent: 0
    design:
      show_skill_percentage: false

  - block: resume-awards
    content:
      title: Awards
      items:
        - title: College Distinction in Service
          date: 2024-05-01
          awarder: Texas State University
          description: "Recognized for departmental and college leadership."
        # - title: Another Award
        #   date: 2022-10-01
        #   awarder: Org Name
        #   description: "Optional description."

  - block: resume-languages
    content:
      title: Languages
      items:
        - name: English
          proficiency: Native
        - name: Spanish
          proficiency: Reading
---
