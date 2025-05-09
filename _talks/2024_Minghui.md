---
title: "Approximate Leave one out CV in High Dimensions"
collection: talks
type: "Talks"
permalink: /talks/2024_Minghui
venue: "Minghui Yu Memorial Conference, Columbia University"
date: 2024-04-01
location: "New York, NY, USA"
---

Slides can be found [here](https://github.com/KyrinZou/lynzou.github.io/files/Slides_Certified_Data_Removal.pdf).
**Abstract:** Machine unlearning focuses on the computationally efficient removal of specific training data from trained models, ensuring that the influence of forgotten data is effectively eliminated without the need for full retraining. Despite advances in low-dimensional settings, where the number of parameters \( p \) is much smaller than the sample size \( n \), extending similar theoretical guarantees to high-dimensional regimes remains challenging. We propose an unlearning algorithm that starts from the original model parameters and performs a theory-guided sequence of Newton steps. After this update, carefully scaled isotropic Laplacian noise is added to the estimate to ensure that any (potential) residual influence of forget data is completely removed. We show that when both $ n, p \to \infty $ with a fixed ratio $ n/p $, significant theoretical and computational obstacles arise due to the interplay between the complexity of the model and the finite signal-to-noise ratio. Finally, we show that, unlike in low-dimensional settings, a single Newton step is insufficient for effective unlearning in high-dimensional problems---however, two steps are enough to achieve the desired certifiebility. We provide numerical experiments to support the certifiability and accuracy claims of this approach. 
