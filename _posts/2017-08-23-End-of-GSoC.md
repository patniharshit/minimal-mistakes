---
layout: post
title: End of GSoC
description: Summary of GSoC 17 project
comments: True
tags: blog
---

This will be the end of the Google Summer of Code 17. This was the first time
when I worked on a big project having evaluations, deadlines and what not. I
also had to come up with a project proposal and timeline beforehand. Good
thing is that I was able to complete the project that I proposed in proposal.

In retrospection I have one regret that I wasted too much time in understanding
what was needed to be done in first month which led to shortage of time in the
end for going beyond what was promised in proposal. Another thing is I should
have done was asking for help earlier than I did on several occasions when I
was stuck or was in doubt. Asking the questions in right way, at right time
and with right background info is an art that should be mastered.

In terms of learning I am definitely better Python programmar than before. I
have much better understanding of OOP, testing, and git. I also learned
several design patters while going through Matplotlib codebase. One chage that
I noticed in myself is that I cannot withstand PEP8 violations anymore.

But most important lesson learnt is in working with such a big codebase of a
library where you can't understand everthing. This is not really a skill in
itself but working with big codebase involves lots of grepping, digging up git
history, git blame, traversing stack  traces, referring documentation and sometimes
guessing too. Few times discussion on closed git issues and PRs also helped.
And many times looking at tests also works.

Towards the end of GSoC I was stuck on few weired errors. For several days
I made some frustrating attempts at debugging them by putting print statments. 
Those attempts were futile as the stack trace isn't linear and later I
discovered that several classes and files were indulged which even included
some C++ code for drawing. This is where I discovered the power of IPython
notebooks in debugging python code with the help of debugger like `ipdb`.
Debugger significantly reduces debug time as well as frustration associated
with it.

One failure was not being able to keep up a schedule for working. In my proposal
I promised 8 hours of work per day. Well it isn't as easy as it seems and
specially when the work is on laptop where it is easy to be distracted by
some notification beep.
