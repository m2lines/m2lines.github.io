---
date: 2026-10-14T09:29:16+10:00
title: "Design and Implementation of a Data-Driven Parameterization for Mesoscale Eddy-Induced Transport"
heroHeading: ''
heroSubHeading: 'Design and Implementation of a Data-Driven Parameterization for Mesoscale Eddy-Induced Transport: Idealized Two-Layer Configurations'
heroBackground: ''
thumbnail:  'images/news/2610Balwada.png'
images: ['images/news/2610Balwada.png']
link: 'https://doi.org/10.1029/2025MS005245'
---

Mesoscale eddies, the ocean’s swirling currents, move heat and tracers and drain potential energy from the large-scale circulation. Most climate models can’t fully resolve them, so their effects are approximated with the Gent-McWilliams (GM) scheme. GM captures the overall energy removal but assumes eddy fluxes always run down the gradient, missing the up-gradient and cross-gradient fluxes seen in reality. It can also dampen eddies that models partially resolve.

In new **M²LInES [work](https://doi.org/10.1029/2025MS005245) led by Dhruv Balwada**, the team developed **a machine learning parameterization free of this diffusive constraint**. Using a small, inexpensive neural network, it captures the full structure of eddy thickness fluxes while still extracting energy, adapts to both the flow and model resolution, and is tuned with a single simple parameter. **Implemented in NOAA GFDL’s MOM6 ocean model**, it performed well in idealized channel and gyre simulations at eddy-permitting and coarse resolutions.