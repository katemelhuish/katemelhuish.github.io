---
title: "Publications"
type: landing

sections:
  - block: collection
    id: publications-grid    # ← add this line
    content:
      title: ""
      filters:
        # Use the folder where your publication bundles live:
        # if your items are in content/publication/, use [publication]
        # if they are in content/publications/, keep [publications]
        folders: [publications]
      count: 0
      sort_by: "Date"
      sort_ascending: false
      search:
        enabled: true
    design:
      # Use a card/grid layout that shows images + summaries
      view: card
      columns: 3      # 1 or 2 columns; 2 gives a nice grid
---
