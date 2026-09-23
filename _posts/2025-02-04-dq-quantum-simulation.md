---
layout: post
title: "dq: Exploring Quantum Simulation with Standard ML and Futhark"
author: Martin Elsman
category: projects
tags: ["quantum computing", "Standard ML", "Futhark", "parallel programming"]
---
{% include JB/setup %}

[dq, the DIKU Quantum Simulation Framework](https://github.com/diku-dk/dq),
provides tools for specifying, drawing, and simulating quantum circuits.
It separates a circuit's description from its execution, making it possible
to explore several simulation strategies using the same circuit.
These range from constructing the matrix that a circuit denotes to operating
directly on a state vector and generating parallel Futhark code for GPUs.

<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="/pdf/array25-publ.pdf#page=2">
    <img src="/images/dq-gate-fusion-circuit.png" width="615" height="368"
         style="display: block; width: 100%; height: auto; margin: 0;"
         alt="Four-qubit quantum circuit with consecutive T, H, and X gates on qubit 3 that can be fused.">
  </a>
  <figcaption style="margin-top: 0.75em; font-size: 0.9em;">
    The consecutive T, H, and X gates on qubit 3 are candidates for gate fusion.
    Figure 1 from <a href="/pdf/array25-publ.pdf#page=2"><em>Gate Fusion Is Map Fusion</em></a>,
    Martin Elsman and Troels Henriksen, ARRAY 2025
    (<a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>).
  </figcaption>
</figure>

The framework connects to the ideas in my posts on
[Kronecker-free quantum simulation at WQS 2025]({% post_url 2025-06-17-kronecker-free-quantum-simulator-wqs %})
and the [PPDP/LOPSTR 2026 paper]({% post_url 2026-08-28-kronecker-free-quantum-simulator-ppdp %}):
avoiding the enormous matrix for an entire circuit while retaining a clear
connection to its mathematical meaning.
Its standalone Futhark gate library also supports fusing consecutive
single-qubit gates on the same qubit, illustrating the connection between
quantum gates and array operations described in
[Gate Fusion Is Map Fusion]({% post_url 2025-06-17-gate-fusion-is-map-fusion %}).

The repository includes examples of Grover's algorithm in both Standard ML
and Futhark, along with a tool for translating qsim circuit files into
Futhark programs. It is a practical starting point for experimenting with
functional descriptions of quantum circuits and their parallel execution.

<div style="clear: both;"></div>
