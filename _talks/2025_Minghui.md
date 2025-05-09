---
title: "Approximate Certified Data Removal in High Dimensional R-ERM"
collection: talks
type: "Talks"
permalink: /talks/2025_Minghui
venue: "Minghui Yu Memorial Conference, Columbia University"
date: 2025-04-18
location: "New York, NY, USA"
---

Slides can be found [here](https://github.com/KyrinZou/lynzou.github.io/files/Slides_Certified_Data_Removal.pdf).

Machine unlearning addresses the challenge of efficiently removing data traces from machine learning mod els when users request their data be deleted. While significant theoretical and empirical advances have been made, current methods are often limited to low-dimensional models, where the number of model parameters is much smaller than the number of observations. This limitation poses a significant obstacle for high dimensional models, which are increasingly common in real-world applications. The primary objective of this paper is to develop certifiable data removal algorithms for high-dimensional settings, where both the number of features (p) and observations (n) are large, and their ratio satisfies n/p ≈ δ, with δ being a fixed constant. Recognizing that traditional definitions of certifiability are overly restrictive and unsuitable for high- dimensional scenarios, we propose a refined definition that incorporates the inherent randomness of the data. Leveraging this revised framework, we design a computationally efficient machine unlearning algorithm applicable to a broad class of learning problems known as regularized empirical risk minimization (R-ERM). 
