---
layout: post
title: "Compositional Deep Learning in Futhark at FHPNC 2019"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


Our paper *Compositional Deep Learning in Futhark*, with Duc Minh Tran and
Troels Henriksen, was accepted for presentation at FHPNC 2019 in Berlin on
August 18.

We show how to build neural networks by composing typed library components,
including dense and convolutional layers. The same structure supports training
through backpropagation and prediction through forward propagation. Futhark
removes the higher-order functions and module abstractions during compilation,
leaving opportunities for fusion and other GPU optimisations. The result
connects a modular way of describing networks with efficient generated code.

[Read the paper (PDF)](/pdf/fhpnc19.pdf).

<div style="clear: both;"></div>
