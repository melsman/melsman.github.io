---
layout: post
title: "Kronecker-Free Quantum Simulation at WQS 2025"
author: Martin Elsman
category: papers
tags: ["quantum computing", "functional programming", "WQS"]
---
{% include JB/setup %}

My extended abstract *Deriving a Kronecker-Free Functional Quantum
Simulator* was accepted for presentation at the 2nd Workshop on Quantum
Software (WQS 2025) in Seoul on June 17.

Quantum circuits have a clear mathematical description in terms of
matrices, but constructing the matrix for an entire circuit soon consumes
too much memory. This work derives a functional interpreter that applies
the circuit directly to its state vector instead. The result avoids the
large intermediate matrix while preserving the circuit's meaning, and
experiments illustrate the performance benefits of the approach.

[Read the extended abstract (PDF)](/pdf/wqs25-final.pdf) or visit the
[workshop presentation page](https://pldi25.sigplan.org/details/wqs-2025-papers/4/Deriving-a-Kronecker-Free-Functional-Quantum-Simulator).
