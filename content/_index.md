---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  # ─── HERO / PROFILE ─────────────────────────────────
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume-subek-acharya.pdf
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

  # ─── FEATURED PUBLICATIONS ──────────────────────────
  - block: collection
    id: featured-publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # ─── FEATURED PROJECTS ──────────────────────────────
  - block: collection
    id: featured-projects
    content:
      title: Featured Projects
      filters:
        folders:
          - projects
        featured_only: true
    design:
      view: article-grid
      columns: 3

  # ─── CONTACT ────────────────────────────────────────
  - block: contact-info
    id: contact
    content:
      title: Get in Touch
      subtitle: 'Open to industry roles and research collaboration in AI/ML.'
      email: subekacharya@gmail.com
      address:
        city: Kingston
        region: RI
        country: United States
    design:
      columns: '1'
---