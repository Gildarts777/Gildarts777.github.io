---
title: 'GTPO: Stabilizing Group Relative Policy Optimization via Gradient and Entropy
  Control'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Marco Simoni*
- Aleksandar Fontana*
- Giulio Rossolini
- Andrea Saracino
- Paolo Mori

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-09T16:36:14.687234Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-arxiv

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2508.03772*'
publication_short: ''

doi: ''

abstract: 'Group Relative Policy Optimization (GRPO) is a promising policy-based approach for Large Language Model alignment, yet its performance is often limited by training instability and suboptimal convergence. In this paper, we identify and analyze two main GRPO issues: (i) the token-level penalization, where valuable tokens shared across different responses receive contradictory feedback signals, leading to conflicting gradient updates that can reduce their likelihood; and (ii) the policy collapse, where negatively rewarded completions may penalize confident responses and shift model decisions toward unlikely tokens, destabilizing training process. To address these issues we introduce GTPO (Group-relative Trajectory-based Policy Optimization), which prevents conflicting gradients on valuable tokens by skipping negative updates while amplifying positive ones and filters out completions whose entropy exceeds a provable threshold, to prevent policy collapse. Unlike GRPO, GTPO does not rely on KL-divergence regularization, eliminating the need for a reference model during training, while still ensuring greater training stability and improved performance, as validated through multiple experiments on GSM8K, MATH, AIME 2024, AIME 2025 and AMC 2023.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2508.03772'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
