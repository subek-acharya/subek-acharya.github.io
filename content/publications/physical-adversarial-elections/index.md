---
title: "Analyzing Physical Adversarial Example Threats to Machine Learning in Election Systems"

authors:
  - Khaleque Md Aashiq Kamal
  - Surya Eada
  - Aayushi Verma
  - me
  - Adrian Yemin
  - Benjamin Fuller
  - Kaleel Mahmood

date: '2026-03-01T00:00:00Z'
publishDate: '2026-03-01T00:00:00Z'

publication_types: ['article']

publication:
  name: "arXiv preprint"
  short_name: "arXiv"

peer_reviewed: false
open_access: true

abstract: "Developments in machine learning for election systems have shown both promising results and risks. Trained models perform well on ballot classification tasks (>99% accuracy) but are at risk from adversarial example attacks that cause misclassifications. In this paper, we analyze an attacker who seeks to deploy adversarial examples against ballot classifier models to compromise an election. We first derive a probabilistic framework for determining the number of adversarial example ballots that must be printed to flip an election, in terms of the probability of each candidate winning and the total number of ballots cast. Second, it is an open question, which type of adversarial example is most effective when physically printed in the voting domain. We analyze six different types of adversarial example attacks: ℓ∞-APGD, ℓ₂-APGD, ℓ₁-APGD, ℓ₀ PGD, ℓ₀+ℓ∞ PGD and ℓ₀+σ-map PGD. Our experiments include physical realizations of 144,000 adversarial examples through printing and scanning with four different machine learning models. We empirically demonstrate an analysis gap exists between the physical and digital domains, wherein adversarial examples most effective in the digital domain (ℓ₂ and ℓ∞) differ substantially from the adversarial examples most effective in the physical domain (ℓ₁ and ℓ₂). By unifying a probabilistic election framework with digital and physical adversarial example evaluations, we move beyond prior close race analyses to explicitly quantify when and how adversarial ballot manipulation could alters election outcomes."

summary: "A large-scale analysis of physical adversarial threats to ML-based election systems using 32,000 printed and scanned adversarial ballot examples to bridge digital and physical attack domains."

tags:
  - Adversarial Machine Learning
  - AI Security
  - Physical Adversarial Attacks
  - Election Systems

featured: false

links:
  - type: pdf
    url: "https://arxiv.org/pdf/2603.00481"
  - type: custom
    name: arXiv
    url: "https://arxiv.org/abs/2603.00481"
  - type: custom
    name: GitHub
    url: "https://anonymous.4open.science/r/A7C27X4/"

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---

**Status**: Preprint available on arXiv.