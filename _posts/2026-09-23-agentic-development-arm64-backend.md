---
layout: post
title: "New report: Agentic Development of an ARM64 Compiler Backend"
author: Martin Elsman
category: technical reports
tags: ["MLKit", "ReML", "compilers", "ARM64"]
---
{% include JB/setup %}

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
