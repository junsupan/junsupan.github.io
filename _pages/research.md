---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Job Market Paper

**Tensor Principal Component Analysis**

* *Abstract:* In this paper, we develop new methods for analyzing high-dimensional tensor datasets. A tensor factor model describes a high-dimensional dataset as a sum of a low-rank component and an idiosyncratic noise, generalizing traditional factor models for panel data. We propose an estimation algorithm, called tensor principal component analysis (TPCA), which generalizes the traditional PCA applicable to panel data. The algorithm involves unfolding the tensor into a sequence of matrices along different dimensions and applying PCA to the unfolded matrices. We provide theoretical results on the consistency and asymptotic distribution for the TPCA estimator of loadings and factors. We also introduce a novel test for the number of factors in a tensor factor model. The TPCA and the test feature good performance in Monte Carlo experiments and are applied to sorted portfolios.

[Download paper here](https://junsupan.github.io/files/Job%20Market%20Paper_Pan.pdf)

[Replication package - Matlab](https://github.com/junsupan/TensorPCA_MatLab)

Recommended citation: Babii, Andrii, Ghysels, Eric, and Pan, Junsu. "Tensor Principal Component Analysis." *arXiv preprint arXiv:2212.12981* (2022).

## Working Paper/Work in Progress

**Tensor Factor Asset Pricing Models,** with Andrii Babii and Eric Ghysels

* This paper provides two additional applications of tensor factor models estimated by TPCA: 1) international asset pricing that involves time, industry and country dimensions, and 2) conditional asset pricing of equities based on (a) the cross-section of individual firm returns, (b) the time series of monthly returns and (c) data encoding characteristics across firms and time.
* The international asset pricing application suggests that there is one world factor and one segmentation factor that together explain the international asset returns.
* The conditional asset pricing application aims to estimate time varying loadings based on the time series behavior of a firm’s characteristics, relative to the entire universe of stocks.

**High-dimensional Dynamic Portfolio Selection with Machine Learning**

* This paper extends the static Markowitz portfolio choice to a dynamic and conditional problem by modeling portfolio weights as a function of characteristics, and incorporates a LASSO-type penalty to select the high-dimensional function coefficients. It outperforms the dynamic portfolio choice problem without a LASSO penalty and the benchmark of static and equally weighted portfolios in terms of out-of-sample Sharpe ratios.
