---
layout: post
title: "sml-server: A New Home for Web Programming in Standard ML"
author: Martin Elsman
category: projects
tags: ["Standard ML", "web programming", "MLKit", "SMLserver"]
---
{% include JB/setup %}

[sml-server](https://github.com/diku-dk/sml-server) provides a small foundation
for writing HTTP servers whose requests are handled by Standard ML code.
It builds on the `sml-http` library and the Standard ML Basis Library's sockets,
and works with both MLKit and MLton. Dependencies are managed with
[smlpkg]({% post_url 2020-03-08-smlpkg-package-manager %}), so the server can be
included as a library in an ordinary Standard ML project.

Together with the
[SMLserver demonstration](https://github.com/melsman/sml-server-demo),
it replaces the earlier, no-longer-supported SMLserver implementation.
The original system ran compiled Standard ML bytecode inside AOLserver;
the new approach compiles the application into an executable that runs its
own HTTP server. It carries forward the idea of using Standard ML's types,
functions, and modules to build web applications, with a simpler deployment
model. The current server is single-threaded.

The demonstration brings together HTML and SQL quotations, PostgreSQL
connectivity, and HTTPS fetching through OpenSSL. It provides a practical
starting point for building database-backed web applications with MLKit.

The earlier work provides the background:

- [Web Programming with SMLserver (PDF)](/pdf/padl2003.pdf), by Martin Elsman
  and Niels Hallenberg, PADL 2003, describes the original server's execution
  model, database access, and experience with web programming in Standard ML.
- [A Region-Based Abstract Machine for the ML Kit (PDF)](/pdf/kam.pdf),
  by Martin Elsman and Niels Hallenberg, technical report TR-2002-18,
  describes the abstract machine underlying the old bytecode-based approach.
- [Typing XHTML Web Applications in ML (PDF)](/pdf/padl2004.pdf), by Martin
  Elsman and Ken Friis Larsen, PADL 2004, explores using types to check
  generated XHTML and the consistency of web forms.
- [SMLserver — A Functional Approach to Web Publishing, Second Edition (PDF)](/pdf/smlserver-book-20070410.pdf),
  by Martin Elsman, Niels Hallenberg, and Carsten Varming, IT University of
  Copenhagen, April 2007, is the book-length account of the earlier system.
