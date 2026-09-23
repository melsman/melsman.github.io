---
layout: post
title: "Exploring Chaos with Futhark: The Feigenbaum Project"
author: Martin Elsman
category: projects
tags: ["Futhark", "parallel programming", "graphics", "chaos"]
---
{% include JB/setup %}

<div style="display: flow-root;" markdown="1">
<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_logistic.png">
    <img src="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_logistic.png" alt="Bifurcation diagram of the logistic map."
         style="display: block; width: 100%; height: auto; margin: 0;" loading="lazy">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; line-height: 1.4;">Bifurcation diagram of the logistic map.</figcaption>
</figure>

My [feigenbaum project](https://github.com/melsman/feigenbaum) uses Futhark
to explore how simple repeated calculations can produce surprisingly intricate
patterns. The application draws bifurcation diagrams: each horizontal position
selects a parameter, and the points above it show values reached after letting
the calculation settle. The familiar logistic map, `x → r × x × (1 − x)`,
reveals branches splitting into finer patterns as its parameter changes.

Built on the Futhark Lys library, the viewer lets you pan, zoom, and switch
between several recurrence equations while exploring their behaviour.

</div>

<div style="display: flow-root;" markdown="1">
<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_sincos.png">
    <img src="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_sincos.png" alt="Bifurcation diagram of the SinCos map."
         style="display: block; width: 100%; height: auto; margin: 0;" loading="lazy">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; line-height: 1.4;">Bifurcation diagram of the SinCos map.</figcaption>
</figure>

The SinCos map combines sine and cosine in a two-variable recurrence,
producing a different collection of bands and branches. The viewer also
includes the tent and Gaussian maps. Comparing these pictures is a hands-on
way to explore how changing a parameter can lead from regular oscillations
to chaotic behaviour.

Futhark computes the diagram's columns in parallel. Each column first runs
some warm-up iterations, then records further values for drawing. The steps
within one recurrence depend on each other, but different parameter values
can be explored independently.

</div>

<div style="display: flow-root;" markdown="1">
<figure style="float: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_henon.png">
    <img src="https://raw.githubusercontent.com/melsman/feigenbaum/master/images/bif_henon.png" alt="Bifurcation diagram of the Hénon map."
         style="display: block; width: 100%; height: auto; margin: 0;" loading="lazy">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; line-height: 1.4;">Bifurcation diagram of the Hénon map.</figcaption>
</figure>

The Hénon map provides another two-variable example to investigate.
The repository also includes an interpreted version of the logistic map:
a small interpreter written in Futhark executes a sequence of instructions
representing the formula. This explores how the same compiled program could
support different recurrence formulas supplied at runtime.

The [repository](https://github.com/melsman/feigenbaum) contains the source,
build instructions, and examples of how to add another recurrence. Use the
arrow keys to navigate, `z` and `x` to zoom, and `1`–`6` to switch examples.
All three images shown here come from the project; click one to see it at
full size.

</div>

