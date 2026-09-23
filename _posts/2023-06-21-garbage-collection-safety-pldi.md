---
layout: post
title: "Garbage-Collection Safety at PLDI 2023"
author: Martin Elsman
category: papers
tags: ["MLKit", "memory management"]
---
{% include JB/setup %}

{% include video-preview.html url="https://www.youtube.com/watch?v=js5IO8XlgdE" image="https://i.ytimg.com/vi/js5IO8XlgdE/hqdefault.jpg" alt="Video thumbnail for Garbage-Collection Safety at PLDI 2023" %}

My paper *Garbage-Collection Safety for Region-Based Type-Polymorphic
Programs* was accepted for presentation at PLDI 2023 in Orlando on June 21.

Combining compiler-directed memory reclamation with garbage collection
requires care: the collector must never encounter a pointer to memory that has
already been freed. This paper identifies a flaw in earlier theory that also
affected a real implementation. A revised region type system tracks collection
effects through higher-order, polymorphic code, repairing the problem while
simplifying function types. The result supports the safe combination of region
inference and partly tag-free garbage collection.

[Read the paper (PDF)](/pdf/gcsafe-pldi23.pdf).

[Conference programme and abstract](https://pldi23.sigplan.org/details/pldi-2023-pldi/10/Garbage-Collection-Safety-for-Region-Based-Type-Polymorphic-Programs).

[Watch my presentation](https://www.youtube.com/watch?v=js5IO8XlgdE).

<div style="clear: both;"></div>
