---
layout: post
title: Towards final weeks
description: Update on work done in first weeks of phase 3 of coding period
comments: True
tags: blog
---

Just before second evaluations I pushed some code to my PR adding
the color square drawing functionality. So this week was mostly
spent in addressing the code reviews on the PR and refactoring
accordingly.

Majorly I fixed up `imshow` function by removing some premptive
calls to norm and cmap. It mostly involved refactoring the code
which was directly using shape of image assuming a 2D array to
make it take shape of bivariate data also.

Currently I am trying to debug some issue with `pcolor` and
`pcolormesh` functions where it hits some strange dimensional
unmatch error in some C++ code on passing in `BivariateNorm` as
norm.
