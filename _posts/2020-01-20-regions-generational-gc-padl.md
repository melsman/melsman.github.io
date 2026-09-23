---
layout: post
title: "Combining Regions and Generational GC at PADL 2020"
author: Martin Elsman
category: papers
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

Our paper *On the Effects of Integrating Region-based Memory Management and
Generational Garbage Collection in ML*, with Niels Hallenberg, was accepted
for presentation at PADL 2020 in New Orleans on January 20.

The compiler can reclaim many values using regions, while a garbage collector
handles more dynamic memory behaviour. This paper investigates what happens
when that collector also separates young and old objects into generations.
Implemented in MLKit, the design uses region types to support partly tag-free
collection and avoid write-barrier problems. Benchmarks compare the
alternatives and show cases where regions and generations complement each
other.

[Read the paper (PDF)](/pdf/padl2020-final.pdf).

[Conference programme and abstract](https://popl20.sigplan.org/home/PADL-2020).
