---
title: Blog
summary: My posts
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: Blog
    content:
      title: Blog
      filters:
        folders:
          - teaching
    design:  
      view: article-grid
      columns: 2
---
