---
layout: post
title: "Kronecker-Free Quantum Simulation at PPDP/LOPSTR 2026"
author: Martin Elsman
category: papers
tags: ["quantum computing", "functional programming", "PPDP"]
---
{% include JB/setup %}

My paper *Deriving a Kronecker-Free Functional Quantum Simulator* was
accepted for presentation at PPDP/LOPSTR 2026 in Indianapolis, with the talk
scheduled for August 28.

A direct mathematical description of a quantum circuit leads to an enormous
matrix, which quickly makes simulation impractical. The paper derives a
purely functional simulator that works directly on the circuit and its
state vector, avoiding that matrix altogether. This keeps the connection
to the circuit's mathematical meaning while substantially reducing the
space needed compared with the full-matrix approach. The paper also
examines the performance benefits of the resulting simulator.

[Read the paper (PDF)](/pdf/ppdp26-final.pdf) or visit the
[conference presentation page](https://icfp26.sigplan.org/details/lopstr-ppdp-2026-papers/14/Deriving-a-Kronecker-Free-Functional-Quantum-Simulator).
