---
title: "PatchGuard Lacks Robustness: Breaking State-Of-The-Art Defect Detection Under New Norm Attacks"

authors:
  - me
  - Syed Ayon
  - Khaleque Md Aashiq Kamal
  - Ruyu Zhou
  - Kaleel Mahmood

date: '2026-09-01T00:00:00Z'
publishDate: '2026-09-01T00:00:00Z'

publication_types: ['paper-conference']

publication:
  name: "IEEE International Symposium on Physical Assurance and Inspection of Electronics (PAINE)"
  short_name: "IEEE PAINE 2026"

peer_reviewed: true
open_access: false

abstract: "Defect detection is critical to the safety and reliability of modern manufacturing systems. Although automated machine learning-based anomaly detection methods have demonstrated strong performance, they remain vulnerable to input manipulation in the form of adversarial examples. In this work, we conduct a comprehensive adversarial robustness evaluation of PatchGuard, a recent state-of-the-art defense for machine learning defect detection. PatchGuard was published at CVPR 2025, and was initially tested only under ℓ∞ norm attacks. We expand its robust evaluation to five white-box attacks spanning four perturbation norms: APGD-ℓ₂, APGD-ℓ₁ and PGD-ℓ₀, APGD-ℓ∞ and PGD-ℓ∞. We evaluate PatchGuard on two benchmark datasets (MVTec and VisA) and demonstrate several important empirical findings. First, for both datasets, the 1,000-step PGD-ℓ∞ attack used in the original publication is never the strongest attack for evaluating PatchGuard's robustness. Second, for undefended models, ℓ∞ and ℓ₁ norm attacks are the most effective (lowest) indicators of robustness. Third, PatchGuard is not robust to ℓ₀ norm attacks. On average, the PatchGuard defense offers only a 1.25% improvement in Image-Level AUROC robustness as compared to a model with no defense for the MVTec dataset. Overall, our results move the field of defect detection security forward by demonstrating the inherent weakness in an ℓ∞ centric defense evaluation. Through evaluating PatchGuard, we show that multi-norm attack analyses are a necessary component for measuring defense fidelity."

summary: "We demonstrate that PatchGuard, a state-of-the-art defect detection defense, is vulnerable to novel adversarial norm attacks across ℓ∞, ℓ₂, ℓ₁, and ℓ₀ perturbations on industrial defect datasets."

tags:
  - Adversarial Machine Learning
  - AI Security
  - Defect Detection
  - Industrial Inspection
  - Adversarial Robustness

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: custom
    name: GitHub
    url: "https://github.com/subek-acharya/Project-Patch"

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---

**Status**: Accepted at IEEE PAINE 2026. Publication forthcoming.