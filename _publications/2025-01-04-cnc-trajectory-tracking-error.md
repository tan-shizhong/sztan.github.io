---
title: "A data-driven rolling optimization method for trajectory tracking error prediction of CNC machine tools"
collection: publications
category: manuscripts
permalink: /publication/2025-cnc-trajectory-tracking-error
excerpt: "Rolling optimization for data-driven CNC feed-drive error prediction under time-varying dynamics using partial weight freezing."
date: 2025-01-04
venue: "Science China Technological Sciences"
authors: "Yinxin Guan, Jixiang Yang, <strong>Shizhong Tan</strong>, and Han Ding"
doi: "10.1007/s11431-024-2785-y"
paperurl: "https://doi.org/10.1007/s11431-024-2785-y"
citation: "Yinxin Guan, Jixiang Yang, <strong>Shizhong Tan</strong>, and Han Ding. (2025). &quot;A data-driven rolling optimization method for trajectory tracking error prediction of CNC machine tools.&quot; <i>Science China Technological Sciences</i>, 68(1), 1120301."
---

<figure class="paper-figure">
  <img src="{{ site.baseurl }}/images/publications/cnc-rolling-optimization.svg" alt="Conceptual diagram of rolling optimization for CNC trajectory tracking-error prediction">
  <figcaption>Common temporal features are retained while the output mapping is quickly updated as feed-drive characteristics change over time.</figcaption>
</figure>

## Short summary

The dynamic performance of CNC feed-drive systems directly affects machining accuracy, but feed-drive behavior can change with load, wear, lubrication, and other time-varying factors. This paper focuses on restoring prediction accuracy quickly when system characteristics drift.

* **Problem:** Conventional data-driven feed-drive models can lose accuracy when machine dynamics change, and full retraining can be data- and time-consuming.
* **Method:** An LSTM-FC model is split into feature-extraction and output-fitting parts. During rolling optimization, feature-extraction weights are frozen to preserve learned motion patterns, while output-fitting weights are updated to adapt to the new data distribution.
* **Effect:** Experiments show that the method reduces maximum prediction error by 49.5% and total training time by 96.3% compared with existing methods.
