---
title: 'Training-Free Adaptive Quantization for Variable Rate Image Coding for Machines'
authors:
  - Yui Tatsumi
  - admin
  - Hiroshi Watanabe
date: '2026-02-03T00:00:00Z'
doi: '10.1109/ICCE67443.2026.11449636'
publication_types: ['paper-conference']
publication: 'In *2026 IEEE 44th International Conference on Consumer Electronics (ICCE 2026)*, pp. 1–6'
publication_short: 'In *IEEE ICCE 2026*'
abstract: >-
  Image Coding for Machines (ICM) has become increasingly important with the rapid integration of computer
  vision technology into real-world applications. However, most neural network-based ICM frameworks operate at a
  fixed rate, thus requiring individual training for each target bitrate. This limitation may restrict their
  practical usage. Existing variable rate image compression approaches mitigate this issue but often rely on
  additional training, which increases computational costs and complicates deployment. Moreover, variable rate
  control has not been thoroughly explored for ICM. To address these challenges, we propose a training-free
  framework for quantization strength control which enables flexible bitrate adjustment. By exploiting the scale
  parameter predicted by the hyperprior network, the proposed method adaptively modulates quantization step
  sizes across both channel and spatial dimensions. This allows the model to preserve semantically important
  regions while coarsely quantizing less critical areas. Our architectural design further enables continuous
  bitrate control through a single parameter. Experimental results demonstrate the effectiveness of our proposed
  method, achieving up to 11.07% BD-rate savings over the non-adaptive variable rate baseline. The code is
  available at https://github.com/qwert-top/AQVR-ICM.
tags: []
featured: false
url_pdf: 'https://arxiv.org/pdf/2511.05836'
url_code: 'https://github.com/qwert-top/AQVR-ICM'
links:
  - name: arXiv
    url: https://arxiv.org/abs/2511.05836
projects: []
---
