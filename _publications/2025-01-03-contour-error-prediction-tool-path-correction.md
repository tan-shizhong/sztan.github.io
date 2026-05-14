---
title: "A contour error prediction method for tool path correction using a multi-feature hybrid model in robotic milling systems"
collection: publications
category: manuscripts
permalink: /publication/2025-contour-error-prediction-tool-path-correction
excerpt: "GP and CNN-BiLSTM contour-error prediction for robotic milling with multi-source features from robot posture, stiffness, and stock allowance."
date: 2025-01-03
venue: "Robotics and Computer-Integrated Manufacturing"
authors: "<strong>Shizhong Tan</strong>, Congcong Ye, Chengxing Wu, Jixiang Yang, and Han Ding"
doi: "10.1016/j.rcim.2024.102936"
paperurl: "https://doi.org/10.1016/j.rcim.2024.102936"
citation: "<strong>Shizhong Tan</strong>, Congcong Ye, Chengxing Wu, Jixiang Yang, and Han Ding. (2025). &quot;A contour error prediction method for tool path correction using a multi-feature hybrid model in robotic milling systems.&quot; <i>Robotics and Computer-Integrated Manufacturing</i>, 93, 102936."
---

<!--
<figure class="paper-figure">
  <img src="{{ site.baseurl }}/images/publications/contour-error-prediction.svg" alt="Conceptual workflow for multi-feature contour-error prediction and robotic milling tool-path correction">
  <figcaption>Robot posture, stiffness, and scanned stock allowance are fused into a structured dataset for contour-error prediction and tool-path correction.</figcaption>
</figure>
-->

## Short summary

High-precision robotic milling is difficult when large workpieces have uneven machining allowances and the robot undergoes pose-dependent stiffness deformation. This paper treats contour error as a multi-source prediction problem rather than relying only on a simplified physical model or repeated trial-and-error correction.

* **Problem:** Contour errors arise from coupled robot posture, stiffness, process disturbance, and non-uniform stock distribution, especially in large cavity-like parts.
* **Method:** Gaussian processes are used to transform multi-source features into a structured dataset, and a CNN-BiLSTM network predicts contour errors by combining local feature extraction with tool-path sequence modeling.
* **Effect:** On a saddle-shaped workpiece similar to aeroengine casing cavities, the model reduces maximum contour error from 0.9629 mm to 0.4881 mm and mean absolute contour error from 0.7171 mm to 0.3048 mm.
