---
layout: post
title: "Compiling APL through TAIL at ARRAY 2014"
author: Martin Elsman
category: papers
tags: ["APL", "TAIL", "compilers", "Futhark"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


Our paper *Compiling a Subset of APL Into a Typed Intermediate Language*,
with Martin Dybdal, was accepted for presentation at ARRAY 2014 in Edinburgh
on June 12.

APL packs powerful array operations into very little code. We introduce TAIL,
a typed array intermediate language that makes the number of dimensions and
element types explicit, while the compiler handles the subtleties of APL's
notation and operators. This gives optimisations a clearer starting point:
we show how to generate efficient C-like code and express operations such as
inner products using simpler array building blocks.

[Read the paper (PDF)](/pdf/array14_final.pdf).
[Workshop programme](https://www.sable.mcgill.ca/array/2014/index.html).

The [apltail project]({% post_url 2014-10-20-apltail-compiler %}) provides the
implementation and examples.

<div style="clear: both;"></div>
