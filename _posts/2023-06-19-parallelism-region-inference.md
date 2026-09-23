---
layout: post
title: "Parallelism in a Region Inference Context at PLDI 2023"
author: Martin Elsman
category: papers
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

{% include video-preview.html url="https://www.youtube.com/watch?v=AcZnDnfZDHE" image="https://i.ytimg.com/vi/AcZnDnfZDHE/hqdefault.jpg" alt="Video thumbnail for Parallelism in a Region Inference Context at PLDI 2023" %}

Our paper *Parallelism in a Region Inference Context*, with Troels Henriksen,
was accepted for presentation at PLDI 2023 in Orlando on June 19.

How can a compiler safely manage memory regions when several computations run
at once? We introduce fork-join parallelism for MLKit and an analysis that
determines which regions need protection during parallel execution. The
compiler uses information about program effects to make those decisions
automatically. The paper develops the underlying type system and its soundness
argument, and benchmarks show that this approach can use multiple CPU cores
effectively in higher-order functional programs.

[Read the paper (PDF)](/pdf/parreg-pldi23.pdf).

[Conference programme and abstract](https://pldi23.sigplan.org/details/pldi-2023-pldi/37/Parallelism-in-a-Region-Inference-Context).

[Watch my presentation](https://www.youtube.com/watch?v=AcZnDnfZDHE).

<div style="clear: both;"></div>
