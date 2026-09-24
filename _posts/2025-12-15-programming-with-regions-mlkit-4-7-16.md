---
layout: post
title: "Programming with Regions in the MLKit: Updated Manual"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "Standard ML", "memory management"]
---
{% include JB/setup %}

<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://elsman.com/mlkit/">
    <img src="/images/ml_kit.svg" alt="MLKit logo"
       style="display: block; width: 100%; height: auto; margin: 0;">
  </a>
</figure>

The technical report *Programming with Regions in the MLKit* is now
available in a revised edition for MLKit 4.7.16, written with Mads Tofte,
Lars Birkedal, Niels Hallenberg, Tommy Højfeld Olesen, and Peter Sestoft.

Compared with the previous listed edition, 4.7.2, this report adds explanations
of double-ended bit-stealing, which gives many algebraic data types more
compact representations, and deep argument flattening, which passes nested
function arguments unboxed and works across compilation units. It also
documents improved automatic conversions in the C interface and clearer
printing of intermediate programs.

The version history additionally records fork-join parallelism and ReML's
explicit regions and effects, while noting that those features are not
covered in detail in this manual. Chapter 20 summarises the changes; the
rest of the report remains a practical guide to region-based memory
management, program representations, and profiling.

[Read the revised manual (PDF)](/pdf/mlkit-4.7.16.pdf).

<div style="clear: both;"></div>
