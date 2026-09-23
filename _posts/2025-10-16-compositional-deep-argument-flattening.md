---
layout: post
title: "Compositional Deep Argument Flattening at ML 2025"
author: Martin Elsman
category: papers
tags: ["MLKit", "compilers", "Standard ML", "ML Workshop"]
---
{% include JB/setup %}

My paper *Compositional Deep Argument Flattening* was accepted for
presentation at the ML Family Workshop 2025 in Singapore on October 16.

Function calls can spend unnecessary time packing values into objects only
for the receiving function to unpack them again. This work lets the
compiler pass components of nested objects directly in registers and
combine curried arguments into more efficient calls. The transformations
can be applied repeatedly alongside other optimisations, even across
separately compiled units. The paper establishes key correctness
properties and reports on the implementation and performance benefits in
MLKit.

[Read the paper (PDF)](/pdf/ml25-deep-flattening.pdf) or see the
[workshop programme](https://conf.researchr.org/home/icfp-splash-2025/mlsymposium-2025).
