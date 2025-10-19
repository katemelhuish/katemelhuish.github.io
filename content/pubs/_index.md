---
title: "Publications"
type: landing
url: /publications/        # <-- takes over the /publications/ path
outputs: ["html"]
---

- block: collection
  content:
    title: "All Publications"
    filters:
      folders: [publications]  # your items live here (plural)
    count: 0
    group_by: year
    sort_by: date_desc
    show_badges: false
    show_image: false
    show_summary: false
    show_authors: true
    show_publication: true
  design:
    view: citation

