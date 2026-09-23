---
layout: post
title: "Irregular Array Comprehensions at TFP 2020"
author: Martin Elsman
category: papers
tags: ["Futhark", "parallel programming"]
---
{% include JB/setup %}

Our extended abstract *Efficient Translation of Certain Irregular
Data-Parallel Array Comprehensions*, with Ken Friis Larsen, was accepted for
presentation at TFP 2020 in Krakow, held alongside Lambda Days. The talk was
scheduled for February 14.

Array comprehensions offer a compact way to describe queries and calculations,
but irregular nesting makes efficient GPU execution difficult. We introduce a
comprehension language supporting nesting, zipping, filtering, and sorting,
and show how to translate it into Futhark using segmented operations. Examples
demonstrate how these familiar abstractions can express useful computations
while still producing efficient parallel code.

[Read the paper (PDF)](/pdf/fut-comprehensions.pdf).

[Conference programme and abstract](https://lambdadays.org/lambdadays2020/ken-friis-larsen/).
