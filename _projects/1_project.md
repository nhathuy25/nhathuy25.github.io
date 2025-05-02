---
layout: page
title: Expanding VAE
description: Progressive Expansion of MLP Layers in Variational Autoencoders
img: assets/img/vae1.png
importance: 1
category: work
related_publications: true
---

This project explores an experimental approach to Variational Autoencoders (VAEs) by progressively expanding the number of neurons in the dense encoder layers. The objective is to assess the impact of increased network capacity on model performance, particularly in terms of image reconstruction and generation.

Key aspects include:

- Implementation of an experimental VAE architecture {% cite kingma2022autoencodingvariationalbayes %}, {% cite doersch2021tutorialvariationalautoencoders %} with progressively increasing encoder layers.
- Evaluation of model performance on the MNIST dataset. {% cite LeCun2005TheMD %}
- Analysis of reconstruction loss and generation quality as the network capacity increases.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/vae1.png" title="VAE Architecture" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/vae2.png" title="Loss Curve" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Left: Diagram of the VAE architecture with expanding encoder layers. Right: Training and validation loss curves over epochs.
</div>

For more details, visit the [GitHub repository](https://github.com/nhathuy25/expanding-VAE).
