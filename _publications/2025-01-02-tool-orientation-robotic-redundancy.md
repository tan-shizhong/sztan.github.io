---
title: "Processing accuracy improvement of robotic ball-end milling by simultaneously optimizing tool orientation and robotic redundancy"
collection: publications
category: manuscripts
permalink: /publication/2025-tool-orientation-robotic-redundancy
excerpt: "Simultaneous optimization of tool orientation and robot redundancy to reduce force-induced tool-tip deformation in robotic ball-end milling."
date: 2025-01-02
venue: "Robotics and Computer-Integrated Manufacturing"
authors: "<strong>Shizhong Tan</strong>, Jixiang Yang, and Han Ding"
doi: "10.1016/j.rcim.2024.102904"
paperurl: "https://doi.org/10.1016/j.rcim.2024.102904"
citation: "<strong>Shizhong Tan</strong>, Jixiang Yang, and Han Ding. (2025). &quot;Processing accuracy improvement of robotic ball-end milling by simultaneously optimizing tool orientation and robotic redundancy.&quot; <i>Robotics and Computer-Integrated Manufacturing</i>, 93, 102904."
---

<figure class="paper-figure">
  <img src="{{ site.baseurl }}/images/publications/tool-orientation-redundancy.svg" alt="Conceptual diagram of tool orientation and robot redundancy optimization for ball-end milling">
  <figcaption>Tool orientation and robotic redundant angle are optimized together to minimize deformation error at the actual tool tip.</figcaption>
</figure>

## Short summary

Robotic ball-end milling is flexible and cost-effective, but the low stiffness of industrial robots causes deformation errors that hurt profile accuracy. Existing posture-optimization studies often focus on end-effector translational deformation or average cutting force, which can miss the real deformation at the tool tip.

* **Problem:** Tool-tip deformation varies with robot posture, tool geometry, and cutting-force changes, making simple end-effector deformation indices insufficient.
* **Method:** The paper introduces a tool-tip deformation error index, develops a fast cutter-workpiece engagement calculation method for changing tool orientations, and uses particle swarm optimization to jointly optimize tool orientation and redundant angle under kinematic and interference constraints.
* **Effect:** Validation on a simplified aeroengine casing shows improved robotic milling accuracy compared with unoptimized settings and prior optimization strategies.
