---
title: 'GVCC: Zero-Shot Generative Video Compression'
summary: A pretrained video generative model serves directly as the decoder, and the transmitted bitstream specifies its generation trajectory, enabling zero-shot video compression at ultra-low bitrates. (NeurIPS 2026)
tags:
  - Deep Learning
  - Generative Compression
date: '2026-03-27T00:00:00Z'
weight: 1

external_link: ''

image:
  caption: Zero-Shot Generative Video Compression
  focal_point: Smart

url_code: ''
url_pdf: 'https://arxiv.org/pdf/2603.26571'
url_slides: ''
url_video: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2603.26571

slides: ""
---

At ultra-low bitrates, high-fidelity reconstruction requires sampling plausible videos from the posterior rather than regressing to oversmoothed conditional means. **GVCC (Generative Video Codebook Codec)** turns a pretrained rectified-flow video generative model into a zero-shot decoder: the deterministic flow sampler is converted into an equivalent marginal-preserving stochastic process, and the transmitted bitstream encodes the per-step stochastic innovations that steer generation.

- **GVCC** works in three practical modes: Text-to-Video (T2V), autoregressive Image-to-Video (I2V) with tail latent correction, and First-Last-Frame-to-Video (FLF2V) with boundary-sharing GOP chaining. **(NeurIPS 2026)**
- **GVCCTurbo** is a BPP-driven scheduler that separates expensive prior refreshes from codebook corrections, turning bitrate into a schedule input and cutting prior evaluations from 20 to 9 (~44% decoding-time reduction).
