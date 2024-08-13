---
title: 'Data Assimilation'
draft: false
featured: true
weight: 1
heroHeading: 'Data Assimilation'
heroSubHeading: ''
heroBackground: '/images/retrosupply-jLwVAUtLOAQ-unsplash.jpeg'
---

<h3 style="text-align: center;">Climate models & observations</h3>

Climate models are powerful tools to simulate and predict the Earth’s climate system, but they aren't without flaws. Due to missing physics, imperfect parameterizations, and inaccuracies in the underlying numerics, climate models often show structural errors. On the other hand we have direct observations of the climate system. However, observations come with their own set of limitations. They have limited space and time coverage and also contain errors due to measurement noise.


<center>
<img src="/images/research/DAillustration-logo.png" style="width: 20vw; padding-bottom: 30px; padding-top: 0px">
</center>
<p style="text-align: left;"><small><b>Figure:</b> Hoteit, I., et al., 2018: Data assimilation in oceanography: Current status and new directions. In "New Frontiers in Operational Oceanography"</small></p>

<h3 style="text-align: center;">Data assimilation</h3>

To overcome  the challenge of uncertainty inherent in both sources of information–models and observations– we employ a method known as data assimilation. Data assimilation merges the information obtained in models and observational data, and produces a “best guess” of the climate system. The schematic above outlines the core process of sequential data assimilation. The model state variables (blue) are continuously adjusted based on the most recent observations (red). This adjustment process (dashed red arrow) is often referred to as the analysis step or analysis increment.

<h3 style="text-align: center;">Learning from analysis increments</h3>

The analysis increments provide useful information on model errors. For example, if the analysis increments always correct the model to a warmer state (i.e., all dashed arrows point upward), this may reflect that the model has a systematic cold bias. Several members of M<sup>2</sup>LInES employ machine learning techniques to learn such model errors from analysis increments.

<h3 style="text-align: center;">Learning model error</h3>

Machine learning algorithms can also be used to understand and correct biases that are due to the combined error of physics and numerics. One way to learn this combined error is to use analysis increments as a training dataset. Analysis increments represent the adjustments made to a model to bring it closer to observations during the data assimilation process. The information contained in analysis increments allows therefore for the development of correction schemes that improve the reliability and accuracy of model predictions.

<h3 style="text-align: center;">Emulation of the full model dynamics</h3>

Another important application of machine learning in climate modeling is the development of emulators. Climate model emulators are surrogate models that mimic the behavior of complex climate models. By capturing the essential features and relationships within the original models, emulators provide a computationally efficient alternative for exploring climate model outputs.
