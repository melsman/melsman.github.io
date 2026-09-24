---
layout: post
title: "Functional Option Pricing at FHPNC 2019"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


Our extended abstract on *A Functional Approach to Accelerating Monte Carlo
based American Option Pricing*, with Wojciech Pawlak and Cosmin Oancea, was
accepted for presentation at FHPNC 2019 in Berlin on August 18.

We explore whether a complex numerical algorithm can be written with
high-level functional building blocks and still run efficiently on a GPU. The
example combines Monte Carlo simulation and regression to price American
options. Its Futhark implementation achieves performance comparable to an
expert CUDA implementation, demonstrating that a concise parallel formulation
can be practical for demanding numerical work.

[Read the paper (PDF)](/pdf/fhpnc19_lsmc.pdf).

<div style="clear: both;"></div>
