---
title: 'Bidirectional Attention-Gated Motion Injection for Frame Interpolation'
authors:
  - admin
  - Yui Tatsumi
  - Hiroshi Watanabe
date: '2025-09-23T00:00:00Z'
doi: '10.1109/GCCE65946.2025.11275014'
publication_types: ['paper-conference']
publication: 'In *2025 IEEE 14th Global Conference on Consumer Electronics (GCCE 2025)*, pp. 53–57. **Oral Presentation Award**'
publication_short: 'In *IEEE GCCE 2025*, **Oral Presentation Award**'
abstract: >-
  We propose Bi-AGMI (Bidirectional Attention-Gated Motion Injection), a lightweight and efficient framework for
  keyframe interpolation based on diffusion models. Bi-AGMI introduces a dual-path denoising process that
  sequentially connects forward and backward sampling trajectories via latent flipping, enabling temporally
  bounded generation from two keyframes. To enhance consistency between these two trajectories, we design a
  novel attention-gated fusion mechanism that dynamically injects and blends forward-path attention features
  into the backward UNet using a learnable gating module. This design improves temporal coherence, mitigates
  motion ambiguity, and eliminates the need for repeated re-noising. Experiments on DAVIS and Pexels datasets
  demonstrate that our method achieves competitive visual quality and inference efficiency compared to recent
  diffusion-based baselines, while requiring significantly fewer sampling steps. By enabling stable
  interpolation over large temporal gaps, Bi-AGMI expands the practical usability of diffusion models for
  long-range video completion.
tags: []
featured: false
url_pdf: ''
url_code: ''
projects:
  - video-coding
---
