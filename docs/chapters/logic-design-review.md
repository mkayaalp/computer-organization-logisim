---
title: Logic Design Review
layout: default
---

A digital logic design course covers the topics of
[combinational](combinational.html) and
[sequential](sequential.html) digital circuits.
We can review the distinction of these circuit types
by showing simple Logisim examples.

For studying computer organization,
we are particularly interested in
[synchronous](synchronous.html) sequential circuits,
which make it easy for us to analyze the
[propagation delay](propagation-clock.html#propagation-delay)
and determine the
[clock period](propagation-clock.html#clock-period) requirements.

One topic that might not have been
paid enough attention in a logic design course is
the very useful
[tri-state buffer](tristate.html).
The Logisim wire coloring is helpful
in showing the cases of "floating"---a wire that is not driven,
and "error"---a wire that is driven to opposite values.
