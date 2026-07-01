---
date: 2026-07-01T09:29:16+10:00
title: " Design principles for stable and generalizable data-driven discretizations for solving linear hyperbolic conservation laws"
heroHeading: ''
heroSubHeading: ''
heroBackground: ''
thumbnail:  'images/news/2607Nasser.png'
images: ['images/news/2607Nasser.png']
link: 'https://doi.org/10.48550/arXiv.2606.17497'
---

Antoine Nasser and Alistair Adcroft investigate how machine learning can be used to develop **stable and accurate numerical schemes for solving the linear advection equation**. Their **[study](https://doi.org/10.48550/arXiv.2606.17497)** identifies the key factors governing the performance of data-driven finite-volume methods, including network architecture, training data, and normalization strategies. They show that data-driven reconstructions based on cell averages are shape-specific, limiting their ability to generalize across different classes of solutions. They introduce a machine-learned flux limiter that improves shape preservation relative to widely used classical schemes and demonstrate that training on polynomial profiles yields stable, high-order accurate discretizations. Overall, the work provides **practical guidelines for designing robust and generalizable machine-learning-based numerical methods for scientific computing.**