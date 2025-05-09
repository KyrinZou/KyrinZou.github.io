---
title: "Approximate Leave-one-out CV for Regression with L1 regularizers"
collection: talks
type: "Talk"
permalink: /talks/2024_AISTATS
venue: "AISTATS 2024"
date: 2024-05-01
location: "Valencia, Spain"
---
The out-of-sample error (OO) is the main quantity of interest in risk estimation and model selection. Leave-one-out cross validation (LO) offers a (nearly) distribution-free yet computationally demanding method to estimate OO. Recent theoretical work showed that approximate leave-one-out cross validation (ALO) is a computationally efficient and statistically reliable estimate of LO (and OO) for generalized linear models with twice differentiable regularizers. For problems involving non-differentiable regularizers, despite significant empirical evidence, the theoretical understanding of ALO’s error remains unknown. In this paper, we present a novel theory for a wide class of problems in the generalized linear model family with the non-differentiable L1 regularizer. We bound the error |ALO−LO| in terms of intuitive metrics such as the size of leave-i-out perturbations in active sets, sample size n, number of features p and signal-to-noise ratio (SNR). As a consequence, for the L1 regularized problems, we show that |ALO−LO|⟶0 when $n,p\to\infty$ while $n/p$ and SNR remain bounded.
