---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in economics specializing in econometrics, financial econometrics, asset pricing, and applied econometrics.

I am working on projects that involve tensors, factor models, portfolio selection, machine learning, etc.

## "Tensor Principal Component Analysis"
A brief introduction to my job market paper:

A **factor model** aims to explain the **co-movements** of large number variables (observable) with only a few factors (variables). For example, a collection of large number of asset returns can be explained by a small number of *"risk factors"* which includes, eg., the market risk, firm size risk, book-market ratio risk, etc. The intuition is that holding each asset should be compensated based on how risky it is, a more risky asset should be expected to pay higher returns for holding such risks, and this is called "risk premium". In the factor model of asset returns, "factor loadings" measure the level of risk for each risk factor.

To visualize a **factor model**:

![This is an alt text.](/files/SVD.png)

However, traditional factor models can only be applied to matrices (panel data), which only has two dimensions - temporal and cross-section. What happens if the data is of more than two dimensions, i.e., a tensor?

A tensor is a **higher dimensional array** - an extension of vectors and matrices:

![This is an alt text.](/files/Tensors.png)

Examples:
* Macro Data: panel of macro indicators + regional dimension
* Sales Data: panel of firms selling products through time

Then a factor model for a 3rd order tensor would look like:

![This is an alt text.](/files/tensor_CPD.png)

We developed the factor model for any *d*-dimensional tensors which is an extension of the traditional factor models, and it is called *tensor factor model*.

The benefits of using ***tensor factor model***:
1. it allows to identify the loadings associated with the additional dimensions,
1. the theory and simulations show improved estimation accuracy with more tensor dimensions,
1. model complexity (# of parameters) is significantly reduced compared to traditional one when you have a tensor data.

For estimation of the *tensor factor model*, we designed an algorithm that is called *Tensor Principal Component Analysis (TPCA)*.

The advantages of ***TPCA***:
1. easy to use in practice: based on PCA,
1. closed-form estimators, avoids non-convex optimization,
1. allows sequential computation of factors.

To read more about this algorithm, the theoretical results, the hypothesis test for selecting number of factors, Monte Carlo simulations, and an empirical application, please [click here](https://arxiv.org/abs/2212.12981) to download the paper. To estimate your own tensor factor model, [click here](https://github.com/junsupan/TensorPCA) to install the Python package.
