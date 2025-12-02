---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      # Gradient background
      background:
        gradient_mesh:
          enable: true

      # Avatar customization
      avatar:
        size: medium   # small | medium | large | xl | xxl
        shape: circle  # circle | square | rounded

  - block: collection
    id: papers
    content:
      title: "Featured Publications"
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: "Recent Publications"
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
