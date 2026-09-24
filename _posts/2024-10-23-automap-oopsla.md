---
layout: post
title: "AUTOMAP at OOPSLA 2024"
author: Martin Elsman
category: papers
tags: ["Futhark", "type systems", "array programming", "OOPSLA"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


Our paper *AUTOMAP: Inferring Rank-Polymorphic Function Applications with
Integer Linear Programming*, with Robert Schenck, Nikolaj Hey Hinnerskov,
Troels Henriksen, and Magnus Madsen, was accepted for presentation at
OOPSLA 2024 in Pasadena, with the talk scheduled for October 23.

Array languages often let an operation on a single value work on a whole
array automatically. AUTOMAP brings that convenience to a statically typed
language: it works out where to insert mapping and replication operations,
while retaining compile-time type checking. The system uses integer linear
programming to find a solution requiring as few inserted operations as
possible. The paper develops the theory and describes an implementation
in Futhark.

[Read the paper (PDF)](/pdf/oopslab24main-p607-final.pdf) or see the
[published article](https://doi.org/10.1145/3689774) and
[OOPSLA programme](https://2024.splashcon.org/track/splash-2024-OOPSLA).

<div style="clear: both;"></div>
