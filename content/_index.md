---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-04-02
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: '📚 My Research & Work'
      subtitle: ''
      text: |-
        I am a PhD student in AI and Cybersecurity at Scuola Superiore Sant'Anna. My primary research focuses on stabilizing Large Language Model alignment. Recently, I proposed GTPO, a trajectory-based policy optimization algorithm that resolves conflicting preference gradients during training. 

        I also apply these techniques to the cybersecurity domain, using Group Relative Policy Optimization (GRPO) to enhance LLM reasoning for software vulnerability detection. On the practical side, I work as an AI Consultant, architecting custom Transformer-based models to classify cyber attacks.

        Feel free to reach out to collaborate 😃
    design:
      columns: '1'

  # ─── SEZIONE 1: JOURNAL ARTICLES ──────────────────────────────────────────
  - block: collection
    id: journals
    content:
      title: Journal Articles
      filters:
        folders:
          - Publications
        # 2 = Journal article
        publication_type: 'Journal-article' 
    design:
      view: citation

  # ─── SEZIONE 2: CONFERENCE PAPERS ─────────────────────────────────────────
  - block: collection
    id: conferences
    content:
      title: Conference Papers
      filters:
        folders:
          - Publications
        publication_type: 'paper-conference'
    design:
      view: citation

  # ─── SEZIONE 3: PREPRINTS & ARXIV ─────────────────────────────────────────
  - block: collection
    id: preprints
    content:
      title: Preprints & Working Papers
      filters:
        folders:
          - Publications
        # 3 = Preprint / Working Paper
        publication_type: 'article-arxiv'
    design:
      view: citation


  # - block: collection
  #   id: news
  #   content:
  #     title: Notes & Updates
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---