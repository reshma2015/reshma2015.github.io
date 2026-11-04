---
title: ''
summary: ''
date: 2026-11-04
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      # TODO: put your CV at static/uploads/resume.pdf, then uncomment
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '📡 My Research'
      subtitle: ''
      # TODO: describe your research
      text: |-
        I work on next-generation wireless and cellular networks. My research spans Open RAN,
        intelligent and programmable RAN control, and over-the-air experimentation on
        5G testbeds.

        Please reach out to collaborate.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
