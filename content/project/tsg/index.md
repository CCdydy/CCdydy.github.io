---
title: "TSG: Time Step Generating"
summary: A universal synthesized deepfake image & video detector that uses a pre-trained diffusion model as a single-pass feature extractor, independent of pretraining models, specific datasets, or sampling algorithms. (ACM MMAsia 2025 Oral)
tags:
  - Deep Learning
  - Deepfake Detection
date: '2024-12-01T00:00:00Z'
weight: 3

external_link: ''

image:
  caption: Deepfake Detection via Time Step Generating
  focal_point: Smart

url_code: 'https://github.com/NuayHL/TimeStepGenerating'
url_pdf: 'https://arxiv.org/pdf/2411.11016'
url_slides: ''
url_video: ''

links:
  - name: arXiv
    url: https://arxiv.org/abs/2411.11016

slides: ""
---

We proposed a general-purpose deepfake image detector called **Time Step Generating (TSG)**. Unlike existing methods, TSG is independent of pretraining model reconstruction abilities, specific datasets, or sampling algorithms. By feeding images to a pre-trained diffusion model at a fixed timestep, TSG captures the differences in noise-prediction behavior between real and generated images within a single forward pass.

To remove the reliance on a manually chosen timestep, **TSG++** consolidates multi-timestep diffusion features through lightweight fine-tuning, improving robustness and generalization without additional inference cost.

We further extended this deepfake detection technique to **fake video detection**, enabling localization of manipulated frames and forged regions.

**Published:** ACM MMAsia 2025 (Oral)
