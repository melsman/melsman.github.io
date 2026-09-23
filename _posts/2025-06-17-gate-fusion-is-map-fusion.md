---
layout: post
title: "Gate Fusion Is Map Fusion at ARRAY 2025"
author: Martin Elsman
category: papers
tags: ["Futhark", "quantum computing", "parallel programming", "ARRAY"]
---
{% include JB/setup %}

{% include video-preview.html url="https://doi.org/10.1145/3736112.3736143" image="/images/dq-gate-fusion-circuit.png" alt="Quantum circuit from Figure 1 of Gate Fusion Is Map Fusion" note=" (ACM Supplemental Material). Circuit: Elsman and Henriksen, Figure 1, <a href='https://creativecommons.org/licenses/by/4.0/'>CC BY 4.0</a>." %}

Our paper *Gate Fusion Is Map Fusion*, with Troels Henriksen, was accepted
for presentation at ARRAY 2025 in Seoul on June 17.

The paper expresses quantum gates as parallel array operations in Futhark.
This makes an important quantum-simulation optimisation a familiar compiler
optimisation: consecutive gates on the same qubits can be combined by
Futhark's existing map-fusion machinery. The approach also allows the state
vector to be updated in place. We explain why the construction is correct
and compare its performance with the qsim and QuEST simulators.

[Read the paper (PDF)](/pdf/array25-publ.pdf) or visit the
[workshop presentation page](https://pldi25.sigplan.org/details/ARRAY-2025-papers/7/Gate-Fusion-is-Map-Fusion).

[Watch my presentation](https://doi.org/10.1145/3736112.3736143)
under **Supplemental Material** in the ACM Digital Library.

<div style="clear: both;"></div>
