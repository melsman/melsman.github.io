---
layout: post
title: "Region Memory Management and Generational GC in JFP"
author: Martin Elsman
category: papers
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

Our paper *Integrating region memory management and tag-free generational
garbage collection*, with Niels Hallenberg, has been published in the *Journal
of Functional Programming*.

Region inference and generational garbage collection both reclaim short-lived
values efficiently, but can they work well together? We present a combined
design in MLKit that uses region information to avoid write-barrier overhead
and some runtime tags. The paper develops formal properties and evaluates
several memory-management configurations. The benchmarks show that adding
generations can improve on non-generational collection, while also revealing
the memory cost of fragmentation.

[Read the paper (PDF)](/pdf/jfp2021.pdf).

[Published article](https://doi.org/10.1017/S0956796821000010).
