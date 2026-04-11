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
  # ─── 1. BIOGRAFIA ───────────────────────────────────────────────────────
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0'] 
      background:
        gradient_mesh:
          enable: true
      date_format: 'January 2006'
      name:
        size: md 
      avatar:
        size: medium 
        shape: circle 

  # ─── 2. ESPERIENZA SPOSTATA IN ALTO ─────────────────────────────────────
  - block: resume-experience
    content:
      title: Experience
      username: me
    design:
      date_format: 'January 2006'

  # ─── 3. TESTO DI RICERCA E LAVORO ───────────────────────────────────────
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

  # ─── 4. CONFERENCE PAPERS ───────────────────────────────────────────────
  - block: collection
    id: conferences
    content:
      title: Conference Papers
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
    design:
      view: citation

  # ─── 5. PREPRINTS & ARXIV ───────────────────────────────────────────────
  - block: collection
    id: preprints
    content:
      title: Preprints & Working Papers
      filters:
        folders:
          - publications
        publication_type: 'article-arxiv'
    design:
      view: citation
---
  # # ─── SEZIONE 1: JOURNAL ARTICLES ──────────────────────────────────────────
  # - block: collection
  #   id: journals
  #   content:
  #     title: Journal Articles
  #     filters:
  #       folders:
  #         - publications
  #       # 2 = Journal article
  #       publication_type: 'article-paper' 
  #   design:
  #     view: citation

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