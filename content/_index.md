---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: portfolio
    id: projects
    content:
      title: Recent projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: SDG Atlas
          tag: SDG Atlas
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: Python
          description:
          icon: python
          icon_pack: fab
        - name: R
          description:
          icon: r-project
          icon_pack: fab
        - name: Stata
          description:
          icon: chart-line
          icon_pack: fas
        - name: Tableau
          description:
          icon: chart-bar
          icon_pack: fas
        - name: GIS
          description:
          icon: map-marked
          icon_pack: fas
        - name: Google Earth Engine
          description: 
          icon: globe-africa
          icon_pack: fas
---
