---
layout: post
title: "apltail: From APL to Typed Array Programs"
author: Martin Elsman
category: projects
tags: ["APL", "TAIL", "compilers", "Futhark"]
---
{% include JB/setup %}

[apltail](https://github.com/melsman/apltail) is a compiler for a subset of
APL, built around TAIL, a typed array intermediate language. It turns compact
APL expressions into explicit array computations that can be inspected,
interpreted, and compiled to C. The repository includes examples ranging from
simple reductions to signal processing and matrix multiplication.

The foundations are described in my post on
[Compiling a Subset of APL Into a Typed Intermediate Language]({% post_url 2014-06-12-compiling-apl-typed-intermediate-language %}).
Later work takes the next step towards GPUs: the post on
[APL on GPUs: A TAIL from the Past, Scribbled in Futhark]({% post_url 2016-09-22-apl-gpus-tail-futhark %})
explains how translating TAIL to Futhark lets the compiler turn high-level
array operations into efficient parallel programs.

For a demonstration, see my presentation
[APL on GPUs – A Progress Report with a Touch of Machine Learning](https://dyalog.tv/Dyalog17/?v=iucPNyTsRt4)
at Dyalog '17 in Elsinore, Denmark. It follows the APL–TAIL–Futhark tool chain
through to GPU execution, including training a neural network to recognise
handwritten digits. The [presentation slides (PDF)](/pdf/Dyalog17.pdf)
are also available.
