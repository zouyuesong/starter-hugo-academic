---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: "widget_page"

sections:
  - block: about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
    design: 
      columns: '2'
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Presentation(s)
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
---
