---
layout: post
title: "smlpkg: A Package Manager for Standard ML"
author: Martin Elsman
category: projects
tags: ["Standard ML", "package management", "Futhark"]
---
{% include JB/setup %}

[smlpkg](https://github.com/diku-dk/smlpkg) makes it easier to share and reuse
Standard ML libraries. It downloads and upgrades dependencies from repositories
such as GitHub and GitLab, using semantic versioning to identify releases.
It is independent of the compiler and fits naturally with MLB files used by
MLton, MLKit, and SMLtoJs.

The everyday workflow is small: `smlpkg add` records a dependency in `sml.pkg`,
and `smlpkg sync` downloads the required packages into the project's `lib`
directory. The resulting source files can then be included in the program's
build in the usual way. This keeps dependency management straightforward
without prescribing how a project should be compiled.

The implementation is an almost complete port to Standard ML of the Futhark
package manager, originally designed and implemented in Haskell by Troels
Henriksen. His post,
[The Present Futhark Package Manager](https://futhark-lang.org/blog/2018-08-03-the-present-futhark-package-manager.html),
explains the design and its emphasis on simple, transparent operations.
For installation instructions and a collection of available Standard ML
packages, see the [smlpkg repository](https://github.com/diku-dk/smlpkg).
