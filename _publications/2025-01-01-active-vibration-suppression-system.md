---
title: "Design of a novel two-DOF robotic active vibration suppression system based on dynamic decoupling and pose-dependent dynamics"
collection: publications
category: manuscripts
permalink: /publication/2025-active-vibration-suppression-system
excerpt: "Two-DOF electromagnetic active vibration suppression for robotic milling with decoupled control, GPR modal prediction, and time-varying LQR."
date: 2026-02-16
venue: "The International Journal of Robotics Research"
authors: "<strong>Shizhong Tan</strong>, Xu Tang, Jixiang Yang, and Han Ding"
doi: "10.1177/02783649261423559"
paperurl: "https://doi.org/10.1177/02783649261423559"
citation: "<strong>Shizhong Tan</strong>, Xu Tang, Jixiang Yang, and Han Ding. (2026). &quot;Design of a novel two-DOF robotic active vibration suppression system based on dynamic decoupling and pose-dependent dynamics.&quot; <i>The International Journal of Robotics Research</i>, 02783649261423559."
---

<figure class="paper-figure">
  <img src="{{ site.baseurl }}/images/publications/active-vibration-suppression.svg" alt="Conceptual diagram of a two-DOF active vibration suppressor for robotic milling">
  <figcaption>A two-DOF electromagnetic suppressor applies controlled forces while a pose-aware controller adapts gains across the robot workspace.</figcaption>
</figure>

## Short summary

Robotic milling can cover large, complex components at lower cost than CNC machines, but low robot stiffness produces coupled vibration and pose-dependent dynamics that degrade machining quality. This paper proposes both hardware and control strategies for active vibration suppression.

* **Problem:** Milling vibration changes with robot pose, and coupled two-direction dynamics make stable suppression difficult over a large workspace.
* **Method:** The work designs a two-DOF electromagnetic dynamic vibration suppressor (EDVS) and a controller combining force dynamic decoupling, Gaussian process regression for pose-dependent modal parameters, and time-varying LQR for adaptive gain updates.
* **Effect:** Long-path, high-speed offset-mass tests and milling experiments verify that the system can suppress vibration robustly under different robot poses.
