---
layout: post
title: "Drawing Bézier Curves with Futhark's expand Operation"
author: Martin Elsman
category: projects
tags: ["Futhark", "parallel programming", "graphics"]
---
{% include JB/setup %}

{% include futhark-logo.html %}


<figure style="float: right; clear: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://github.com/melsman/futhark-bezier">
    <img src="https://raw.githubusercontent.com/melsman/futhark-bezier/master/images/bezier.png" alt="Bézier curve example from the futhark-bezier application"
         style="display: block; width: 100%; height: auto; margin: 0;">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em; line-height: 1.4;">
    Drawing Bézier curves with Futhark. Image from the project repository.
  </figcaption>
</figure>

My [futhark-bezier](https://github.com/melsman/futhark-bezier) project draws cubic Bézier curves in Futhark.
It is a visual example of the `expand` operation defined in our paper
[Data-Parallel Flattening by Expansion](/pdf/array19.pdf), with Troels Henriksen and Niels G. W. Serup.
Different curves can require different amounts of drawing work, making this an irregular parallel problem.
The `expand` operation turns those varying amounts of work into a flat array that can be processed in parallel.

The application builds on the Futhark Lys library and includes an interactive demo.
It also supports antialiased line drawing, with partial support for antialiasing cubic curves.
This makes it a concrete way to explore the connection between a reusable parallel operation and graphics.
The repository includes the source code and instructions for building and running the application.
Try it out to see flattening by expansion at work on something you can draw!

<div style="clear: both;"></div>
