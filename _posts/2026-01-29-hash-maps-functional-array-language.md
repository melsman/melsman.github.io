---
layout: post
title: "Hash Maps in a Functional Array Language at TFP 2026"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming", "hash maps", "TFP"]
---
{% include JB/setup %}

Our paper *Hash Maps in a Functional Array Language*, with William Henrich
Due and Troels Henriksen, was accepted for presentation at TFP 2026 in
Odense and appears in the draft proceedings. It was scheduled for January
29.

We show how to build static, collision-free hash maps in Futhark using
parallel array operations, with an interface that also accommodates keys
of varying sizes. GPU benchmarks show improvements over tree- and
search-based alternatives, but also a gap to NVIDIA's cuCollections
library. The paper uses that comparison to explore what functional array
languages and their compilers need to express efficient hash-map
algorithms.

[Read the paper (PDF)](/pdf/tfp26-paper-07.pdf) or see the
[TFP programme](https://trendsfp.github.io/2026/schedule.html).
