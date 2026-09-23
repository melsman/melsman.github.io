---
layout: post
title: "Incremental Flattening at PPoPP 2019"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

Our paper *Incremental Flattening for Nested Data Parallelism*, with Troels
Henriksen, Frederik Thorøe, and Cosmin Oancea, was accepted for presentation
at PPoPP 2019 in Washington, DC, on February 18.

The best way to parallelise a nested computation depends on both the GPU and
the input size. Instead of choosing one strategy for every case, our compiler
generates several versions that expose different amounts of parallelism.
Automatically tuned thresholds select a suitable version at runtime.
Integrated into Futhark, the approach delivers substantial performance
improvements on financial applications and GPU benchmarks.

[Read the paper (PDF)](/pdf/ppopp19.pdf).

[Conference programme and abstract](https://ppopp19.sigplan.org/details/PPoPP-2019-papers/20/Incremental-Flattening-for-Nested-Data-Parallelism).
