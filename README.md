# HalluciRoots
Uncovering the root causes of hallucination.


> Tracing the origins, mechanisms, and root causes of hallucinations in Vision-Language Models.



## Overview

**HalluciRoots** is a curated research repository focused on understanding **why Vision-Language Models (VLMs) hallucinate**.

Instead of organizing papers only by benchmarks or mitigation methods, this repository maps hallucination research by its possible root causes, including:

- Cross-modal misalignment
- Visual representation instability
- Attention degradation
- Language prior bias
- Spurious correlations
- Weak visual grounding
- Decoding dynamics
- Uncertainty and self-awareness
- Causal mechanisms

## Research Motivation

Vision-Language Models can generate fluent and convincing responses, but they may describe objects, attributes, relations, or events that are not present in the input image.

This repository is built around one central question:

> **Where do hallucinations in Vision-Language Models come from?**
---
## Taxonomy
# 🌳 Taxonomy

```text
Hallucination in Vision-Language Models
│
├── Data-Level Causes
│   ├── Dataset Bias
│   ├── Annotation Bias
│   ├── Distribution Bias
│   └── Counterfactual Data Bias
│
├── Language Priors
│   ├── Object Co-occurrence
│   ├── Frequency Bias
│   └── Statistical Priors
│
├── Spurious Correlations
│   ├── Object-Background Correlation
│   ├── Shortcut Learning
│   └── Contextual Bias
│
├── Representation-Level Causes
│   ├── Visual Feature Instability
│   ├── Internal Representation Drift
│   └── Latent Space Misalignment
│
├── Cross-modal Alignment
│   ├── Feature Misalignment
│   ├── Semantic Misalignment
│   └── Preference Misalignment
│
├── Attention-Level Causes
│   ├── Attention Degradation
│   ├── Over-trust in Summary Tokens
│   └── Weak Image-token Attention
│
├── Grounding-Level Causes
│   ├── Weak Object Grounding
│   ├── Attribute Grounding Failure
│   └── Relation Grounding Failure
│
├── Decoding-Level Causes
│   ├── Autoregressive Error Propagation
│   ├── Visual Information Fading
│   └── Language-prior Dominance
│
├── Uncertainty
│   ├── Epistemic Uncertainty
│   ├── Aleatoric Uncertainty
│   └── Confidence Calibration
│
└── Causal Analysis
    ├── Counterfactual Intervention
    ├── Causal Dependency Discovery
    └── Mechanism Tracing
```
```markdown
# 📚 Root Causes

| Category | Papers |
|----------|---------|
| 🗂 Data Bias | [Open](papers/data_bias.md) |
| 🔗 Spurious Correlation | [Open](papers/spurious_correlation.md) |
| 🧠 Language Prior | [Open](papers/language_prior.md) |
| 🎯 Representation Instability | [Open](papers/representation.md) |
| 👁 Attention Mechanism | [Open](papers/attention.md) |
| 📍 Visual Grounding | [Open](papers/grounding.md) |
| ⚙ Decoding Dynamics | [Open](papers/decoding.md) |
| ❓ Uncertainty | [Open](papers/uncertainty.md) |
| 🔬 Causal Analysis | [Open](papers/causality.md) |
```

