---
layout: post
title: "Programming with Regions in the MLKit: Version 4.7.2"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://elsman.com/mlkit/">
    <img src="/images/ml_kit.svg" alt="MLKit logo"
       style="display: block; width: 100%; height: auto; margin: 0;">
  </a>
</figure>

The revised technical report *Programming with Regions in the MLKit* documents
MLKit 4.7.2. It is joint work with Mads Tofte, Lars Birkedal, Niels
Hallenberg, Tommy Højfeld Olesen, and Peter Sestoft.

This edition updates the manual for a simpler region type system: it removes
the old association between type variables and region variables, along with
the concept of word regions. It also covers the repair to garbage-collection
safety that prevents dangling pointers when region inference is combined with
tracing collection. These changes update the foundations behind the manual's
practical explanations of memory regions, program representations, and
profiling. Chapter 20 summarises the changes since version 4.6.1.

[Read the report (PDF)](/pdf/mlkit-4.7.2.pdf).

<div style="clear: both;"></div>
