---
title: Black-Box Adversarial Attack Framework
date: 2026-01-01
weight: 60
featured: false

summary: A comprehensive black-box adversarial attack framework in PyTorch implementing four state-of-the-art attack methods (RayS, ADBA, Square, SurFree) across ℓ∞ and ℓ₂ perturbation norms.

tags:
  - Adversarial ML
  - Black-Box Attacks
  - PyTorch
  - AI Security
  - RayS
  - Square Attack

links:
  - type: code
    name: GitHub
    url: https://github.com/subek-acharya/Linf-L2-BlackBox-Adversarial-Attack

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

A unified PyTorch framework for evaluating black-box adversarial robustness with four state-of-the-art attack methods:

- **RayS**: A ray searching method for hard-label attacks
- **ADBA**: Adversarial Decision-Based Attack
- **Square Attack**: A query-efficient black-box attack via random search
- **SurFree**: Surface-free black-box attack

The framework supports both **ℓ∞** and **ℓ₂** perturbation norms, providing researchers with a comprehensive toolkit for benchmarking adversarial defenses. Modular design enables easy extension with new attack methods and target models.