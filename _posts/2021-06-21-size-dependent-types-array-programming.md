---
layout: post
title: "Size-Dependent Types for Array Programming at ARRAY 2021"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

Our paper *Towards Size-Dependent Types for Array Programming*, with Troels
Henriksen, was accepted for presentation at the virtual ARRAY 2021 workshop on
June 21.

A matrix multiplication should not fail halfway through a program because its
dimensions do not match. We show how to express array-size constraints in an
ML-style type system, catching many such mistakes before execution without
requiring full dependent types. The system automatically handles the
bookkeeping for sizes that are not statically known. A Futhark implementation
and a study of 44 representative programs explore how well this deliberately
simple design works in practice.

[Read the paper (PDF)](/pdf/array21-final-publ.pdf).

[Conference programme and abstract](https://pldi21.sigplan.org/details/ARRAY-2021-papers/5/Towards-size-dependent-types-for-array-programming).
