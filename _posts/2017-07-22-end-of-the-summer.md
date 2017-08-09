---
layout: post
title: End of the summer
description: Update on work done in last weeks of phase 2 of coding period
comments: True
tags: blog
---

So here I am at the end of the last third day of my summer vacations. As always
3 months passed away real quick and when I look back to these three months I
feel I couldn't get enough of them. But on the bright side did few things
that were on my todo list for long time. Also tried my hands at cooking, started
reading non-fiction, completed few TV series, leveled up in chess and caught up
on messed up insomanic sleeping habits.

Talking about the GSoC project, worked on 2d colorbar or colorsquare this past
week. It was fairly easy task given the code for colorbar was already there
for my referance. The completion of colorsquare brings me in line with the
project timeline too. 

![bivariate-map](http://i.imgur.com/zzW2bZc.png)

While doing random google searches I came across this paper on plotting
climate data with bivaraite maps which proposes the exact same design
adopted by us. Which is basically using the exsisting plotting mechanism
by mapping bivariate data to univariate by norms and using them to index
the bivariate colormap which has been flattened to stored in the form of
1d look up table.

[Bivariate Maps for plotting climate data](http://edepot.wur.nl/172104)

Another interesting paper I came across was based on some pyschophysical
experiments coducted to find out perceptual bivariate color schemes.

[Perceptual Color Scales for Univariate and Bivariate Data Display](http://www.imaging.org/site/PDFS/Papers/2006/ICIS-0-736/33706.pdf)

I also had a long due web meeting with my mentors today. Discussed current
progress and status of project and plan for the concluding month of GSoC.

Note - This is a work in progress and haven't been merged to matplotlib yet.
