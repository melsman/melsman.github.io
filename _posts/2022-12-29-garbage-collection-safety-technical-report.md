---
layout: post
title: "New report: Garbage-Collection Safety for Polymorphic Programs"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

My DIKU technical report *Garbage-Collection Safety for Region-Based
Type-Polymorphic Programs* examines a subtle problem in combining region-based
memory management with garbage collection.

Earlier theory could allow the collector to encounter a dangling pointer in
higher-order, polymorphic programs, and the problem also appeared in an
implementation. The report develops a revised type system that accounts for
garbage-collection effects and explains how to adapt region inference and its
supporting analyses. This restores the safety guarantee while allowing simpler
type schemes for functions.

[Read the report (PDF)](/pdf/gcsafety-revisited-tr-2022.pdf).
