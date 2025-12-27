---
title: "Contact"
type: landing
design:
  spacing:
    padding: ['0', '0', '0', '0']
sections:
  - block: hero
    content:
      title: "Get in Touch"
      text: |
        I’m happy to connect about research, collaborations, and professional opportunities.
        <br><br>
        **Email:** <melhuish@txstate.edu><br>
        **Office:** Department of Mathematics, Texas State University<br>
        San Marcos, TX, USA
    design:
      align: left

  - block: contact
    content:
      title: "Send a Message"
      text: ""
      form:
        action: "https://formspree.io/f/mlgegdwy"
        netlify: false
        fields:
          - type: text
            name: name
            label: "Your name"
            required: true
          - type: email
            name: email
            label: "Your email"
            required: true
          - type: textarea
            name: message
            label: "Your message"
            required: true
        submit_label: "Send message"
      # Optional override for form labels visibility
      dropdown: false
    design:
      columns: "1"
---
