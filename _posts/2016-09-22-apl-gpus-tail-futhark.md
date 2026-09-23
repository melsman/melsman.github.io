---
layout: post
title: "APL on GPUs through TAIL and Futhark at FHPC 2016"
author: Martin Elsman
category: papers
tags: ["APL", "TAIL", "compilers", "Futhark"]
---
{% include JB/setup %}

Our paper *APL on GPUs: A TAIL from the Past, Scribbled in Futhark*,
with Troels Henriksen, Martin Dybdal, Henrik Urms, Anna Sofie Kiehn,
Daniel Gavin, Hjalte Abelskov, and Cosmin Oancea, was accepted for presentation
at FHPC 2016 in Nara, Japan, on September 22.

Can concise APL programs take advantage of a GPU without handwritten GPU code?
We show how to translate a functional subset of APL through TAIL into Futhark,
letting Futhark optimise the array computations and generate parallel code.
The resulting programs can work with Python for visualisation and interaction,
including a Mandelbrot explorer and Conway's Game of Life. Our experiments
show substantial speedups over sequential C, reaching hundreds of times faster
on some benchmarks.

[Read the paper (PDF)](/pdf/fhpc16futhark.pdf).
[Workshop programme](https://icfp16.sigplan.org/track/FHPC-2016-papers).

See also the [apltail project post]({% post_url 2014-10-20-apltail-compiler %}),
which links to my later Dyalog presentation of the compiler tool chain.
