---
title: ''
summary: ''
date: 2026-11-04
type: landing

sections:
  # Profile: photo, name, role, bio, interests, education, social links (from data/authors/me.yaml)
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

  # News: newest first, date in brackets at the end (like the reference sites)
  - block: markdown
    id: news
    content:
      title: '📰 News'
      text: |-
        <!-- TODO: replace with your news items, newest first -->
        - Joined the Institute for the Wireless Internet of Things at Northeastern University as a Postdoctoral Research Fellow. **[Month YYYY]**
        - Paper "TITLE" accepted at VENUE. **[Month YYYY]**
        - Gave a talk on TOPIC at EVENT. **[Month YYYY]**
    design:
      columns: '1'

  # Openings / collaboration note (optional — delete this block if not needed)
  - block: markdown
    content:
      title: '🤝 Collaboration'
      text: |-
        I am always happy to discuss research collaborations in wireless networks and Open RAN.
        Feel free to [get in touch](contact/).
    design:
      columns: '1'
---
