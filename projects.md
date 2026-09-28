---
layout: page
title: Projects
group: navigation
---
{% include JB/setup %}

* <span class="project-logos"><a href="https://elsman.com/mlkit/"><img src="/images/ml_kit.svg" alt="MLKit logo"></a><a href="https://elsman.com/mlkit/smltojs.html"><img src="/images/smltojs_logo_transparent_small.png" alt="SMLtoJs logo"></a></span>
  **[MLKit](https://elsman.com/mlkit/)** is a compiler for
  [Standard ML](https://sml-family.org/) with native backends and a JavaScript
  backend, [SMLtoJs](https://elsman.com/mlkit/smltojs.html). SMLtoJs brings
  Standard ML's static typing, higher-order functions, pattern matching, and
  modules to client-side web programming. The
  [SMLtoJs IDE](https://diku-dk.github.io/sml-ide/) lets you write and run
  Standard ML directly in your browser.

* <span class="project-logos"><a href="https://elsman.com/mlkit/"><img src="/images/reml.svg" alt="ReML logo"></a></span>
  **[ReML](https://elsman.com/mlkit/reml.html)** extends Standard ML with
  effect and memory region annotations. Built on MLKit, it combines inference
  with explicit control over where values live and which effects code may
  perform, allowing the compiler to check those constraints.

* <span class="project-logos"><a href="https://futhark-lang.org/"><img src="/images/futhark-logo.svg" alt="Futhark logo"></a></span>
  **[Futhark](https://futhark-lang.org/)** is a functional language for
  efficient data-parallel programming. My contributions involve language
  design, formal development and techniques for zero-cost abstractions,
  and data-parallel techniques and libraries, including the
  [monoidal library](https://github.com/diku-dk/monoidal). The book
  [Parallel Programming in Futhark](https://futhark-book.readthedocs.io/)
  introduces the language and its approach to parallel programming.

* **[Dq — the DIKU Quantum Simulator](https://github.com/diku-dk/dq)**
  provides tools for specifying, drawing, and simulating quantum circuits.
  It explores functional simulation techniques in Standard ML and parallel
  execution through Futhark, including gate fusion.

* **[Caddie](https://github.com/diku-dk/caddie)** is an experimental
  implementation of combinatory automatic differentiation in Standard ML.
  It represents derivatives as compositions of linear maps and supports
  both forward-mode and reverse-mode differentiation. The approach is described
  in [Combinatory Adjoints and Differentiation (PDF)](/pdf/msfp22.pdf).

* **[APLtoTail](https://github.com/melsman/apltail)** compiles a subset of
  APL into TAIL, a typed array intermediate language. The project includes
  an interpreter and a C backend. Its foundations are described in
  [Compiling a Subset of APL Into a Typed Intermediate Language (PDF)](/pdf/array14_final.pdf).
  APLtoTail has also been used to compile
  APL to Futhark for efficient GPU execution, as described in
  [APL on GPUs: A TAIL from the Past, Scribbled in Futhark (PDF)](/pdf/fhpc16futhark.pdf).
{: .project-list}

## Retired projects

* [SMLserver](http://www.smlserver.org/) is a Web server plugin for
the [Apache](http://www.apache.org/) Web server. SMLserver makes it possible to write dynamic
Web applications using your favorite programming language without
sacrificing efficiency and scalability of your Web service. SMLserver
includes the possibility of accessing a variety of different
relational database management systems (RDBMSs), such as [Oracle](http://www.oracle.com/) and
[Postgresql](http://www.postgresql.org/). This project is retired and has been superseded by
[sml-server](https://github.com/diku-dk/sml-server), a library for building
HTTP servers in Standard ML.
