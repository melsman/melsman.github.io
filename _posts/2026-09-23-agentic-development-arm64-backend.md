---
layout: post
title: "New report: Agentic Development of an ARM64 Compiler Backend"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "ReML", "compilers", "ARM64"]
---
{% include JB/setup %}

<figure style="float: right; clear: right; width: 30%; margin: 0 0 1em 1.5em;">
  <a href="https://elsman.com/mlkit/">
    <img src="/images/reml.svg" alt="ReML logo"
         style="display: block; width: 100%; height: auto; margin: 0;">
  </a>
</figure>

<figure style="float: right; clear: right; width: 15%; margin: 0 0 1em 1.5em;">
  <a href="https://www.apple.com/newsroom/2022/06/apple-unveils-m2-with-breakthrough-performance-and-capabilities/">
    <img src="/images/apple-m2.png" alt="Apple M2 chip on a white background"
         style="display: block; width: 100%; height: auto; margin: 0; background: white;">
  </a>
  <figcaption style="margin-top: 0.5em; font-size: 0.9em;">Image: Apple.</figcaption>
</figure>

My new DIKU technical report, *Agentic Development of an ARM64 Compiler
Backend*, describes bringing MLKit and ReML to Apple Silicon with the help
of a coding agent.

The report follows the work from an initial specification to native
compilers that can compile themselves, integrate with the runtime, and
support interactive execution. It explains how expert guidance, automated
checks, and repeated performance tuning shaped the result in approximately
two days of human work. Benchmarks compare the native backend with the
existing X64 backend running through Rosetta 2, and the report discusses
both the gains and the limitations of this experience.

[Read the technical report (PDF)](/pdf/arm64.pdf).

<div style="clear: both;"></div>
