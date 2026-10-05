---
title: "Black-Box Adversarial Example Attacks on Machine Learning Based Election Systems"

authors:
  - me
  - Syed Ayon
  - Khaleque Md Aashiq Kamal
  - Alina Barnett
  - Surya Eada
  - Kaleel Mahmood

date: '2026-09-01T00:00:00Z'
publishDate: '2026-09-01T00:00:00Z'

publication_types: ['article']

publication:
  name: "Preprint"
  short_name: "Preprint"

peer_reviewed: false
open_access: true

abstract: "Machine learning models have shown exceptional accuracy for ballot classification in election systems. Recent research has demonstrated that these ballot classification models are vulnerable to adversarial example attacks. This is a critical security issue because a successful attack could alter the outcome of an election and undermine the democratic process. However, all adversarial example attacks in the voting domain have assumed a white-box threat model, where the classifier parameters are known. In this work, we advance the field of machine learning in election systems by analyzing a realistic black-box adversary. We implement and evaluate eleven state-of-the-art black-box attacks: query based attacks ADBA, Square, SurFree, RayS, and SA-MOO. We also test adaptive transfer based black-box attacks with APGD-ℓ∞, APGD-ℓ₂, APGD-ℓ₁, PGD ℓ₀, PGD ℓ₀+ℓ∞, and PGD ℓ₀+σ. Our attacks span multiple different norms (ℓ∞, ℓ₂, ℓ₁, and ℓ₀) and three different black-box adversarial threat models (decision based, score based and transfer based). In addition to digital analyses, we physically print and scan 20,000 adversarial examples to evaluate the real-world performance of different black-box attacks. Our finding demonstrate an even larger physical-digital robustness gap exists for black-box adversarial examples than for white-box adversarial examples. Lastly, we conduct the first ever adversarial example transferability study in the voting domain and test adversarial training and barrier zones as two possible black-box defense strategies."

summary: "A comprehensive black-box adversarial attack framework evaluating 11 attacks across multiple perturbation norms on ML-based election systems, revealing critical vulnerabilities in ballot verification models."

tags:
  - Adversarial Machine Learning
  - AI Security
  - Black-Box Attacks
  - Election Systems
  - Ballot Verification

featured: true

links:
  - type: custom
    name: GitHub
    url: "https://anonymous.4open.science/r/Voting-Black-Box-5F12"

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---

**Status**: Preprint. Manuscript under preparation for submission.