---
title: 'GVCCTurbo: Rate-Compute Quality Scheduling for Codebook Driven Generative Compression'
authors:
  - admin
  - Dingjie Peng
  - Xun Su
  - Hiroshi Watanabe
date: '2026-08-04T00:00:00Z'
doi: ''
publication_types: ['article']
publication: '*arXiv preprint arXiv:2608.03517*'
publication_short: '*arXiv:2608.03517*'
abstract: >-
  Codebook-driven generative compression uses a pretrained image or video generator as a zero-shot visual prior
  and transmits compact codebook indices to guide reconstruction at ultra-low bitrate. Current codecs tie each
  finite-rate correction to a fresh prior evaluation, so shortening the sampler also removes correction slots
  that carry target-dependent information. We propose GVCCTurbo, a BPP-driven scheduler that separates expensive
  prior refreshes from codebook corrections: after calibrating an atom-count operating point and skip-gap ratio
  once per protocol, it maps a target codebook-payload bitrate to a trajectory length and refresh period, making
  BPP a schedule input instead of a fixed consequence of sampler length. The same endpoint-prediction and
  finite-rate steering interface covers GVCC-style rectified-flow video and DDCM-style diffusion image
  compression, preserving zero-training deployment and compatibility with future distilled priors. Native 1080p
  curves position the complete zero-shot codec in the ultra-low-bitrate regime. In a controlled 720p Wan-GVCC
  study, the scheduler cuts prior evaluations from 20 to 9 for a ~44% measured decoding-time reduction shared
  across the whole schedule family, at a small shared LPIPS cost on high-motion content; within that family,
  uniform refresh thinning (pure-skip) is a boundary point, and the BPP-aware interior point trades 2.9% fewer
  codebook-payload bits for consistently higher PSNR at comparable LPIPS. These results support BPP-to-compute
  scheduling as a controllable extension of sampler-length tuning, without requiring the allocated point to
  dominate every boundary point.
tags: []
featured: false
url_pdf: 'https://arxiv.org/pdf/2608.03517'
url_code: ''
links:
  - name: arXiv
    url: https://arxiv.org/abs/2608.03517
projects:
  - video-coding
---
