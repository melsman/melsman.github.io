---
layout: post
title: "Caddie: Exploring Combinatory Automatic Differentiation"
author: Martin Elsman
category: projects
tags: ["Standard ML", "automatic differentiation", "functional programming"]
---
{% include JB/setup %}



[Caddie](https://github.com/diku-dk/caddie) is an experimental implementation
of combinatory automatic differentiation, written in Standard ML. It explores
how to turn a description of a calculation into code that computes its
derivatives, supporting both forward-mode and reverse-mode differentiation.

The central idea is to represent a derivative as a composition of small
linear operations. Caddie first translates an expression into combinatory
form, then constructs a linear-map representation of its derivative.
Interpreting that representation gives forward-mode differentiation; taking
its adjoint before interpreting it gives reverse-mode differentiation.
Intermediate results are shared using `let` bindings, keeping generated
expressions from growing unnecessarily.

Much of the implementation follows our paper
[Combinatory Adjoints and Differentiation]({% post_url 2022-04-02-combinatory-adjoints-differentiation %}),
with Fritz Henglein, Robin Kaarsgaard, Mikkel Kragh Mathiesen, and Robert
Schenck. The [paper (PDF)](/pdf/msfp22.pdf) develops the mathematical ideas
behind this approach.

The repository walks through an example based on `ln(x1 * cos(x2))` and
includes runnable examples embedded in Standard ML. Its choice of value
representation allows experiments with evaluating results directly or
constructing code for another language, with efficient gradient generation
for languages such as Futhark as a longer-term aim. See the
[code and examples](https://github.com/diku-dk/caddie) to explore the
transformations step by step.

<div style="clear: both;"></div>
