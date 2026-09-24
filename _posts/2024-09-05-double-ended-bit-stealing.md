---
layout: post
title: "Double-Ended Bit-Stealing at ICFP 2024"
author: Martin Elsman
category: papers
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

<figure style="float: right; clear: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://elsman.com/mlkit/">
    <img src="/images/ml_kit.svg" alt="MLKit logo"
         style="display: block; width: 100%; height: auto; margin: 0;">
  </a>
</figure>

{% include video-preview.html url="https://www.youtube.com/watch?v=3BEHTVi9UNM" image="https://i.ytimg.com/vi/3BEHTVi9UNM/hqdefault.jpg" alt="Video thumbnail for Double-Ended Bit-Stealing at ICFP 2024" %}

My paper *Double-Ended Bit-Stealing for Algebraic Data Types* was accepted for
presentation at ICFP 2024 in Milan, with the talk on September 5.

Functional programs rely heavily on data structures such as trees and syntax
representations. This paper shows how to make many of them more compact by
using spare bits at both ends of a machine word to identify their
constructors. The technique avoids some extra allocations while keeping a
uniform representation of values. Implemented in MLKit, it improves memory use
and delivers speedups on affected benchmarks, including around 9% when
compiling MLKit itself and MLton.

[Read the paper (PDF)](/pdf/icfp24main-p22-final.pdf).

[Conference programme and abstract](https://icfp24.sigplan.org/details/icfp-2024-papers/5/Double-Ended-Bit-Stealing-for-Algebraic-Data-Types).

[Watch my presentation](https://www.youtube.com/watch?v=3BEHTVi9UNM).

<div style="clear: both;"></div>
