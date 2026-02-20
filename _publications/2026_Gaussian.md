---
title: "Gaussian certified unlearning in high dimensions: A hypothesis testing approach."
collection: publications
category: conferences
permalink: /publication/2026_Gaussian
excerpt: 'Selected for oral presentation'
date: 2026-02-14
venue: 'The Fourteenth International Conference on Learning Representations'
paperurl: 'https://openreview.net/forum?id=0FJYicpOj0'
citation: 'Pandey, A., Auddy, A., Zou, H., Maleki, A. and Kulkarni, S. (2026). &quot;Gaussian certified unlearning in high dimensions: A hypothesis testing approach.&quot; <i>The Fourteenth International Conference on Learning Representations</i>.'
---

Machine unlearning seeks to efficiently remove the influence of selected data while preserving generalization. Significant progress has been made in low dimensions, where the dimension of the parameter is much smaller than the sample size, but high dimensions, including proportional regimes , pose serious theoretical challenges as standard optimization assumptions of strong convexity and smoothness of the per-example loss rarely hold simultaneously in proportional regimes. In this work, we introduce Gaussian certifiability, a canonical and robust notion well-suited to high dimensional regimes, that optimally captures a broad class of noise adding mechanisms. Then we theoretically analyze the performance of a widely used unlearning algorithm based on one step of the Newton method in the high-dimensional setting described above. Our analysis shows that a single Newton step, followed by a well-calibrated Gaussian noise, is sufficient to achieve both privacy and accuracy in this setting. This result stands in sharp contrast to the only prior work that analyzes machine unlearning in high dimensions (Zou et al. 2025), which relaxes some of the standard optimization assumptions for high-dimensional applicability, but operates under the notion of certifiability. That work concludes %that a single Newton step is insufficient even for removing a single data point, and that at least two steps are required to ensure both privacy and accuracy. Our result leads us to conclude that the discrepancy in the number of steps arises because of the sub optimality of the notion of certifiability and its incompatibility with noise adding mechanisms, which Gaussian certifiability is able to overcome optimally.
