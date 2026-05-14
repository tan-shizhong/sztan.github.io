---
title: "A prediction and compensation method of robot tracking error considering pose-dependent load decomposition"
collection: publications
category: manuscripts
permalink: /publication/2023-robot-tracking-error-load-decomposition
excerpt: "TCN-based robot joint tracking-error prediction and pre-compensation that accounts for pose-dependent terminal-load effects."
date: 2023-01-01
venue: "Robotics and Computer-Integrated Manufacturing"
authors: "<strong>Shizhong Tan</strong>, Jixiang Yang, and Han Ding"
doi: "10.1016/j.rcim.2022.102476"
paperurl: "https://doi.org/10.1016/j.rcim.2022.102476"
citation: "<strong>Shizhong Tan</strong>, Jixiang Yang, and Han Ding. (2023). &quot;A prediction and compensation method of robot tracking error considering pose-dependent load decomposition.&quot; <i>Robotics and Computer-Integrated Manufacturing</i>, 80, 102476."
---

<!--
<figure class="paper-figure">
  <img src="{{ site.baseurl }}/images/publications/tracking-error-load.svg" alt="Conceptual workflow for pose-dependent load decomposition and robot tracking-error compensation">
  <figcaption>Pose-dependent terminal-load effects are decomposed into joint-level features, used to predict tracking error, and pre-compensated in the robot motion command.</figcaption>
</figure>
-->

## Short summary

Industrial robots are attractive for flexible manufacturing, but their dynamic joint tracking errors limit high-precision machining. This paper addresses the fact that terminal load gravity affects different robot postures differently, and that many data-driven compensation methods ignore this pose-dependent load effect.

* **Problem:** Dynamic tracking errors occur during robotic machining, and the same terminal load can induce different joint errors under different poses.
* **Method:** A temporal convolutional network (TCN) predicts joint tracking errors using position, velocity, and joint-level load-decomposition features. Long continuous trajectories are split into shorter sequences to enlarge the effective training dataset.
* **Effect:** Predicted joint errors are pre-compensated in the motion commands, improving tool-center-point and tool-orientation tracking accuracy in robotic manufacturing tasks.
