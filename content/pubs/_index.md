---
title: "Publications"
type: landing
url: /publications/          # this page serves /publications/
outputs: ["html"]

sections:
  - block: collection
    content:
      title: "All Publications"
      filters:
        folders: [publications]   # matches your items folder (plural)
      count: 0
      group_by: year
      sort_by: date_desc
      show_badges: false
      show_image: true
      show_summary: false
      show_authors: true
      show_publication: true
    design:
      view: citation
---
