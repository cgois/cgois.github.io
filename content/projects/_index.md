---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Current Projects
      text: Here is a selection of projects that I am currently working on.
      filters:
        folders:
          - projects
        tags:
          - current
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: true
      show_read_more: false
  - block: collection
    content:
      title: Previous Projects
      text: Here is a selection of projects that I have previously worked on.
      filters:
        folders:
          - projects
        tags:
          - finished 
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
