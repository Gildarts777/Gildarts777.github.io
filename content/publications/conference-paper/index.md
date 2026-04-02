---
title: 'Unmasking Model Behavior: How LLMs Reason on Vulnerability Detection'

# Authors
authors:
  - me
  - Marco Simoni

# Author notes (optional) - Lasciato vuoto perché non c'è l'asterisco di "equal contribution" in questo paper specifico
author_notes: []

# Data di pubblicazione (approssimata al 2025)
date: '2025-08-10T00:00:00Z'
publishDate: '2025-08-10T00:00:00Z'

# Publication type.
# 1 = Conference paper
publication_types: ['Conference-paper']

# Publication name and optional abbreviated publication name.
publication: In *Availability, Reliability and Security* (ARES 2025)

abstract: "Understanding and controlling the behavior of Large Language Models (LLMs) is crucial for their reliable use in software vulnerability detection. While LLMs show promising zero-shot capabilities, our analysis shows that they often behave inconsistently by over-predicting vulnerabilities, overlooking real vulnerabilities in domain shifts. In this paper, we approach vulnerability detection as a behavior shaping problem. We apply Group Relative Policy Optimization (GRPO) to guide the behavior of models through structured rule-based rewards. Our reward verifiers target both the accuracy of predictions and the coherence of explanations, encouraging the model to develop stable and trustworthy decision patterns. Through experiments on BigVul, DiverseVul and CleanVul benchmarks, we show that behavior shaping with GRPO improves the model's ability to generalize across projects, programming languages, and data quality levels. Furthermore, we show that tuning the regularization's strength of the Kullback--Leibler (KL) divergence enables a balance between risk-seeking and risk-averse behavior, reducing false negatives without overwhelming users with false positives."

summary: "We apply Group Relative Policy Optimization (GRPO) to guide LLM behavior in vulnerability detection, improving generalization and balancing risk-seeking/risk-averse behavior."

tags:
  - Large Language Models
  - Vulnerability Detection
  - GRPO
  - Reinforcement Learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    isbn: "978-3-032-00639-4"


---
