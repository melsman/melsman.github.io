---
layout: post
title: "New report: Generic Combinators for Monoid Nesting in Futhark"
author: Martin Elsman
category: technical reports
tags: ["Futhark", "parallel programming", "monoids"]
---
{% include JB/setup %}

My new DIKU technical report, *Generic Combinators for Monoid Nesting in
Futhark*, explores how to combine parsing and aggregation into a single
parallel query.

The library builds larger queries from small components, using associative
operations that let different parts of the input be processed in parallel.
It handles numbers, delimiter-separated groups, and parentheses with a
fixed nesting bound, without building syntax trees or intermediate
sequences. Correctness proofs support the constructions, while CPU and GPU
experiments show how the choice of representation and the way input is
divided into blocks affect performance.

[Read the technical report (PDF)](/pdf/monoids.pdf).
