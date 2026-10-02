---
title: 'Time Step Generating: A Universal Synthesized Deepfake Image Detector'
authors:
  - admin
  - Yupei Guo
  - Haoyuan Liu
  - Dingjie Peng
  - Hiroshi Watanabe
date: '2025-12-06T00:00:00Z'
doi: '10.1145/3743093.3770967'
publication_types: ['paper-conference']
publication: 'In *Proceedings of the 7th ACM International Conference on Multimedia in Asia (MMAsia 2025)*, pp. 1–8. **Oral**'
publication_short: 'In *ACM MMAsia 2025* (Oral)'
abstract: >-
  The rise of high-fidelity text-to-image diffusion models has made synthetic images increasingly
  indistinguishable from real ones, posing serious threats in digital security and media integrity. Existing
  detection methods often rely on reconstruction-based pipelines, which are computationally expensive and
  brittle on out-of-distribution data. We propose Time Step Generating (TSG), a universal synthetic image
  detector that leverages a pre-trained diffusion model as a feature extractor. By inputting images at a fixed
  diffusion timestep, TSG captures semantic and structural differences in noise prediction behavior between real
  and generated images — all within a single forward pass, enabling lightweight and effective classification. To
  eliminate the reliance on the manually chosen timestep hyperparameter, we further introduce TSG++, an enhanced
  version that consolidates multi-timestep diffusion features through lightweight fine-tuning. TSG++ learns to
  align features across all timesteps, producing a unified representation that improves both robustness and
  generalization without additional inference cost. Experiments on GenImage and challenging multimedia datasets
  demonstrate that TSG and TSG++ outperform prior methods in both accuracy and efficiency, offering a strong and
  adaptable solution for diffusion-based synthetic image detection.
tags: []
featured: true
url_pdf: 'https://arxiv.org/pdf/2411.11016'
url_code: 'https://github.com/NuayHL/TimeStepGenerating'
links:
  - name: arXiv
    url: https://arxiv.org/abs/2411.11016
projects:
  - tsg
---
