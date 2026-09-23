---
layout: post
title: "New report: Crafting a REPL for HOT Compiled Execution"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "ReML", "Standard ML", "REPL"]
---
{% include JB/setup %}

My new DIKU technical report, *Crafting a REPL for HOT Compiled Execution*,
explores how to give an optimising native compiler an interactive prompt.

The design builds on MLKit's incremental compilation: each declaration
becomes native code that is loaded into a persistent running session, where
earlier values remain available. The compiler also supplies the information
needed to print results, even when their compact runtime representations
omit type tags. The same machinery supports separately compiled libraries,
bringing interactive exploration and compiled execution together for MLKit
and ReML.

[Read the technical report (PDF)](/pdf/repl.pdf).
