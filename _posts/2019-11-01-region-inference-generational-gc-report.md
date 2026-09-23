---
layout: post
title: "New report: Combining Region Inference and Generational GC"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

<!-- The report and Papers page specify November 2019 only; the post uses the first day of that publication month. -->

Our DIKU technical report *Combining Region Inference and Generational Garbage
Collection*, with Niels Hallenberg, is available as Technical Report 2019/01.

We investigate how compiler-inferred memory regions interact with a collector
that treats young and old objects differently. The MLKit implementation uses
region information to support partly tag-free collection and avoid
write-barrier problems. Comparisons with MLton and several MLKit
configurations show that, although regions already handle many short-lived
values, generations can still help. The report explains the implementation and
examines its performance trade-offs.

[Read the report (PDF)](/pdf/gengc-techreport.pdf).
