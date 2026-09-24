---
layout: post
title: "Data-Parallel Flattening by Expansion at ARRAY 2019"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


{% include video-preview.html url="https://www.youtube.com/watch?v=g7PoouwWqeU" image="https://i.ytimg.com/vi/g7PoouwWqeU/hqdefault.jpg" alt="Video thumbnail for Data-Parallel Flattening by Expansion at ARRAY 2019" %}

Our paper *Data-Parallel Flattening by Expansion*, with Troels Henriksen and
Niels G. W. Serup, was accepted for presentation at ARRAY 2019 in Phoenix on
June 22.

Irregular parallel problems can be awkward to map onto GPUs, especially when
different inputs produce different amounts of work. We introduce a reusable
higher-order function that expands such work into flat parallel operations,
hiding the details of segmented processing inside a library. Implemented in
Futhark, the technique applies to a range of irregular problems and produces
efficient GPU code without requiring programmers to write their own flattening
machinery.

[Read the paper (PDF)](/pdf/array19.pdf).

[Conference programme and abstract](https://pldi19.sigplan.org/home/ARRAY-2019).

[Watch my presentation](https://www.youtube.com/watch?v=g7PoouwWqeU).

<div style="clear: both;"></div>
