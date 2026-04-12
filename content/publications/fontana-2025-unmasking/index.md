---
title: 'Unmasking model behavior: How llms reason on vulnerability detection'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Aleksandar Fontana
- Marco Simoni

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-04-09T16:36:14.676275Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*International Conference on Availability, Reliability and Security*'
publication_short: ''

doi: ''

abstract: 'Understanding and controlling the behavior of Large Language Models (LLMs) is crucial for their reliable use in software vulnerability detection. While LLMs show promising zero-shot capabilities, our analysis shows that they often behave inconsistently by over-predicting vulnerabilities, overlooking real vulnerabilities in domain shifts. In this paper, we approach vulnerability detection as a behavior shaping problem. We apply Group Relative Policy Optimization (GRPO) to guide the behavior of models through structured rule-based rewards. Our reward verifiers target both the accuracy of predictions and the coherence of explanations, encouraging the model to develop stable and trustworthy decision patterns. Through experiments on BigVul, DiverseVul and CleanVul benchmarks, we show that behavior shaping with GRPO improves the model’s ability to generalize across projects, programming languages, and data quality levels. Furthermore, we show that tuning the regularization’s strength of the Kullback–Leibler (KL) divergence enables a balance between risk-seeking and risk-averse behavior, reducing false negatives without overwhelming users with false positives.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-032-00639-4_18'
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

