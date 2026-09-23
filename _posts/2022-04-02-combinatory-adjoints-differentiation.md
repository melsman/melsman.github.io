---
layout: post
title: "Combinatory Adjoints and Differentiation at MSFP 2022"
author: Martin Elsman
category: papers
tags: ["automatic differentiation", "functional programming"]
---
{% include JB/setup %}

Our paper *Combinatory Adjoints and Differentiation*, with Fritz Henglein,
Robin Kaarsgaard, Mikkel Kragh Mathiesen, and Robert Schenck, was accepted for
presentation at MSFP 2022 in Munich on April 2.

Automatic differentiation is central to tasks such as training neural
networks. We describe derivatives as compositions of linear functions,
avoiding the enormous matrices that a direct representation could require. A
symbolic calculation of adjoints then gives the behaviour of reverse-mode
differentiation. Because the representation retains the original program's
parallel operations, it also creates opportunities for optimisation and
efficient parallel execution.

[Read the paper (PDF)](/pdf/msfp22.pdf).

[Conference programme and abstract](https://msfp-workshop.github.io/msfp2022/).

The [Caddie project]({% post_url 2021-07-16-caddie-combinatory-differentiation %})
provides a Standard ML implementation exploring these ideas, with examples
of forward-mode and reverse-mode differentiation.
