---
layout: page
title: Ecohydrology
description: R package to simulate soil water balance and vegetation growth
img: /assets/img/img_ecohydrology2.jpg
importance: 1
category: work
---



## Summary

In this project, the vegetation growth represented by the
Normalized Difference Vegetation Index (NDVI) is simulated coupled with a soil
water balance model.
The details of the model and parametrization is described in [Souza et al. (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1002/hyp.10953).

We made a simple R package named [Ecohydmod](https://cran.r-project.org/web/packages/Ecohydmod/index.html)
which includes the models and a function to simulate rainfall series using Poisson Process.



### Soil water balance

$$n Z_r \frac{ds}{dt} = R(t) - C_I(R,N) - Q(R,s) - L(s) - ET(s,N)$$

### Vegetation growth



$$\frac{dN}{dt} = k_A A(s) [N_{max} - N] - k_R [N - N_{min}]$$
