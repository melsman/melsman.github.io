---
layout: post
title: "Functional GPU Option Pricing at IFL 2019"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


<!-- Post dated to the first day of IFL 2019; the individual presentation day could not be verified. -->

Our paper *A Functional Approach to Accelerating Monte Carlo based American
Option Pricing*, with Wojciech Pawlak and Cosmin Oancea, was accepted for
presentation at IFL 2019 in Singapore, held on September 25–27.

The paper expresses a demanding simulation algorithm using high-level parallel
functions in Futhark. It combines Monte Carlo simulation with least-squares
regression to value options that can be exercised before expiry. GPU
benchmarks achieve performance comparable to, and in some cases better than, a
CUDA implementation optimised by NVIDIA engineers. The functional formulation
also makes the algorithm easier to inspect and change.

[Read the paper (PDF)](https://futhark-lang.org/publications/ifl19.pdf).

<div style="clear: both;"></div>
