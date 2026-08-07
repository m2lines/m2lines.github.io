---
date: 2026-08-06T09:29:16+10:00
title: " Hard conservation correctors can hide a degrading model when training autoregressive emulators"
heroHeading: ''
heroSubHeading: ''
heroBackground: ''
thumbnail:  'images/news/2608-Chapman.png'
images: ['images/news/2608-Chapman.png']
link: 'https://doi.org/10.48550/arXiv.2607.18416'
---

**Will Chapman** et al. investigate an important challenge in developing **physically consistent AI weather and climate emulators.** The [study](https://doi.org/10.48550/arXiv.2607.18416) shows that enforcing exact water-budget conservation during training can inadvertently allow precipitation biases to grow, even when the final corrected output appears physically perfect. By introducing a revised training strategy that supervises the raw model predictions while penalizing budget imbalances, the authors **restore stable learning** and demonstrate that **exact budget closure alone is not sufficient to ensure physically meaningful AI models.**
