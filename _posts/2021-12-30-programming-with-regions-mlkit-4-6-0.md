---
layout: post
title: "Programming with Regions in the MLKit: Version 4.6.0"
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

The revised technical report *Programming with Regions in the MLKit* is
available for MLKit 4.6.0, written with Mads Tofte, Lars Birkedal, Niels
Hallenberg, Tommy Højfeld Olesen, and Peter Sestoft.

Compared with the previous listed edition, 4.3.0, this report brings the
manual up to date with native x64 code generation, floating-point register
allocation, and 64-bit integer and word types. It also records the addition of
generational garbage collection, the SMLtoJs JavaScript backend, and broader
Basis Library support for sockets and Unix programming. The revised examples
and descriptions connect these developments to the practical use of regions
and memory profiling; Chapter 20 collects the version changes.

[Read the report (PDF)](/pdf/mlkit-4.6.0.pdf).

<div style="clear: both;"></div>
