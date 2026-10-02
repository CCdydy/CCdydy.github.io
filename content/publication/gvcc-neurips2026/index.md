---
title: 'GVCC: Zero-Shot Video Compression via Codebook-Driven Stochastic Rectified Flow'
authors:
  - admin
  - Xun Su
  - Haoyuan Liu
  - Bingyu Lu
  - Yui Tatsumi
  - Hiroshi Watanabe
date: '2026-09-25T00:00:00Z'
doi: ''
publication_types: ['paper-conference']
publication: 'In *The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS 2026)*, to appear'
publication_short: 'In *NeurIPS 2026* (to appear)'
abstract: >-
  At ultra-low bitrates, high-fidelity reconstruction requires sampling plausible videos from the posterior
  rather than regressing to oversmoothed conditional means. We propose Generative Video Codebook Codec (GVCC), a
  zero-shot framework in which a pretrained video generative model serves directly as the decoder, and the
  transmitted bitstream specifies its generation trajectory. Modern rectified-flow video models are typically
  sampled with deterministic ODE solvers, which leave no per-step stochastic channel for transmitting compressed
  information. GVCC addresses this by converting the deterministic flow sampler into an equivalent
  marginal-preserving stochastic process, so that information can be transmitted by encoding the per-step
  stochastic innovations. Unlike images, videos introduce longer temporal dependencies and more diverse
  conditioning modes. We instantiate GVCC in three practical modes: Text-to-Video (T2V) without a reference
  frame, autoregressive Image-to-Video (I2V) with tail latent correction, and First-Last-Frame-to-Video (FLF2V)
  with boundary-sharing Group of Pictures (GOP) chaining. On the seven-sequence UVG dataset, local atom-count
  sweeps characterize the rate–quality behavior of all three variants. We report full-dataset perceptual and
  fidelity metrics together with temporal diagnostics, without inferring matched-rate or global RD improvements
  from these limited local sweeps.
tags: []
featured: false
url_pdf: 'https://arxiv.org/pdf/2603.26571'
url_code: ''
links:
  - name: arXiv
    url: https://arxiv.org/abs/2603.26571
projects:
  - gvcc
---
