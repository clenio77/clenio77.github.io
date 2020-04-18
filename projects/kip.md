---
layout: project
type: project
image: images/kip.png
title: Knowledge-is-Power (KiP)
permalink: projects/kip
date: 2013
labels:
  - Smart Grid
  - Java
  - Power Quality
summary: A hardware and software platform for measuring wall power metrics.
---

<img class="ui image" src="{{ site.baseurl }}/images/kip-screenshot.png">

KiP consists of two components.

### Hardware
The first component is a hardware board which measures power quality information. It takes non-intrusive measurements
and sends that information over IP using UDP to the KiP software for analysis. The board was designed to be built
cheaply (less than $20) and also with simplicity in mind.

### Software
The second component is the KiP software which receives measurements from the board and calculates voltage,
watts, and amperage. The data can be displayed in real time and can also be stored for later analysis.

For more information, please see our github page: <a href="http://anthonyjchriste.github.io/knowledge-is-power/">
<i class="large github icon "></i>knowledge-is-power</a>.

