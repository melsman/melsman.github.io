---
layout: post
title: "Shape-Constrained Array Programming at FHPNC 2023"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

Our paper *Shape-Constrained Array Programming with Size-Dependent Types*,
with Lubin Bailly and Troels Henriksen, was accepted for presentation at FHPNC
2023 in Seattle on September 4.

Many array operations require their inputs to have matching dimensions. This
work makes those requirements part of the type system, catching shape
mismatches at compile time while allowing sizes to be expressed as
computations. The system also handles sizes that become known only at runtime,
such as the length of a filtered array, and uses dynamic checks where
necessary. We establish its soundness and explain how to bring the design into
Futhark.

[Read the paper (PDF)](/pdf/fhpnc23.pdf).
