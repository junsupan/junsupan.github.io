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

A brief introduction to my job market paper - "Tensor Principal Component Analysis":

A factor model aims to explain the **co-movements** of large number variables (observable) with only a few factors (variables). For example, a collection of large number of asset returns can be explained by a small number of *"risk factors"* which includes, eg., the market risk, firm size risk, book-market ratio risk, etc. The intuition is that holding each asset should be compensated based on how risky it is, a more risky asset should be expected to pay higher returns for holding such risks, and this is called "risk premium". In the factor model of asset returns, "factor loadings" measure the level of risk for each risk factor.

To visualize a factor model:

![This is an alt text.](/files/matrix_CPD.png)

However, traditional factor models can only be applied to matrices (panel data), which only has two dimensions - temporal and cross-section. What happens if the data is of more than two dimensions, i.e., a tensor?

A tensor is a higher dimensional array - an extension of vectors and matrices:

![This is an alt text.](/files/Tensors.png)

Examples:\
* Macro Data: panel of macro indicators + regional dimension
* Sales Data: panel of firms selling products through time
