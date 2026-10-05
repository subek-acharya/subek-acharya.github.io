---
title: Adaptive Black-Box Adversarial Attack Framework
date: 2026-06-01
weight: 10
featured: true

summary: A black-box adversarial attack framework that trains a synthetic substitute model using oracle-labeled data, then executes six white-box attacks across multiple perturbation norms to generate transferable adversarial examples.

tags:
  - Adversarial ML
  - Black-Box Attacks
  - Transfer Attacks
  - PyTorch
  - AI Security

links:
  - type: code
    name: GitHub
    url: https://github.com/subek-acharya/AdaptiveBlackBoxAttack

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

Developed a comprehensive black-box adversarial attack framework that leverages the transferability property of adversarial examples. The framework:

- Trains a synthetic substitute model using oracle-labeled data queried from the target black-box model
- Executes six white-box adversarial attacks (across ℓ∞, ℓ₂, ℓ₁, ℓ₀ norms) on the substitute model
- Transfers generated adversarial examples to the target model for effective black-box attacks
- Supports multiple architectures including ResNet, VGG, and DenseNet

Built with PyTorch, this framework demonstrates how adaptive substitute training can produce highly transferable adversarial examples, exposing critical vulnerabilities in deployed ML systems.