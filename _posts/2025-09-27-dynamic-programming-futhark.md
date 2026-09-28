---
layout: post
title: "Dynamic Programming in Futhark"
author: Martin Elsman
category: notes
tags: ["Futhark", "dynamic programming", "parallel programming", "automatic differentiation"]
---
{% include JB/setup %}

{% include futhark-logo.html %}

My note *Dynamic Programming in Futhark* explains how to use the `dpsolve`
library to solve numerical fixed-point problems and compute solutions to
many problem instances in parallel on GPUs.

The solver starts with successive approximations, then switches to Newton's
method to converge more quickly. Through examples in one and several
dimensions, the note shows how to set up these calculations in Futhark.
Automatic differentiation can supply the Jacobian matrices needed by
Newton's method, saving the programmer from deriving and implementing
those derivatives by hand.

The result is a practical introduction to combining numerical methods,
automatic differentiation, and data-parallel execution. The examples begin
with finding the intersection of a circle and a quadratic curve, making the
solver's behaviour easy to explore before moving to larger problems.

[Read the note (PDF, September 27, 2025)](/pdf/dpsolve-2025-09-27.pdf).
An [earlier version (PDF)](/pdf/dpsolver_demo.pdf) is also available.

<div style="clear: both;"></div>
