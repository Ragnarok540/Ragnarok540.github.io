---
layout: post
title:  "Fallacies of Distributed Computing"
date:   2019-08-09 12:00:00 -0500
categories: software
---
Hello! In this post we will briefly explore the so called `Fallacies of Distributed Computing`, that were first drafted by [Peter Deutsch][peter] in 1994 while working at [Sun Microsystems][sun], and 25 years later are still relevant.

The `Fallacies of Distributed Computing` are a series of 7 assumptions that inexperienced software architects are likely to make when designing distributed systems, these assumptions become problems and correcting them can be very expensive the longer the project is allowed to continue while ignoring this issues.

In 1997, [James Gosling][james] included a new fallacy, taking the total to 8:

* __The Network is Reliable__
* __Latency is Zero__
* __Bandwidth is Infinite__
* __The Network is Secure__
* __Topology Doesn't Change__
* __There is one Administrator__
* __Transport Cost is Zero__
* __The network is Homogeneus__

That's about it for today's topic. Peace.

[peter]: https://en.wikipedia.org/wiki/L._Peter_Deutsch
[james]: https://en.wikipedia.org/wiki/James_Gosling
[sun]: https://en.wikipedia.org/wiki/Sun_Microsystems

