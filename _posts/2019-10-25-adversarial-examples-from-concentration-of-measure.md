---
layout: post
title: Adversarial Examples from Concentration of Measure
---

[Saeed Mahloujifar](https://www.cs.virginia.edu/~sm5fd/)<br>
Department of Computer Science<br>
University of Virginia

- **Date**: Friday October 25th, 2019
- **Time**: 12:00PM
- **Location**: Rice 242

**Abstract** Many recent works have shown that adversarial instances that fool classifiers can be found by adding a small perturbation to a normally sampled input. In this talk, I will present a connection between adversarial examples and the well-known phenomenon of “concentration of measure” in high dimensional metric probability spaces. In two recent work [1,2] we show that if the metric probability space of the test instance is concentrated, any classifier with some initial constant error is inherently vulnerable to adversarial perturbations, if the perturbation is allowed to be sublinear in input’s total size. Although many theoretically natural probability spaces (e.g. isotropic Gaussian) are known to be concentrated, it is not clear whether these theoretical results apply to actual distributions such as images. I will also discuss results from a more recent work [3], in which we present a method for empirically measuring and bounding the concentration of a concrete dataset which is proven to converge to the actual concentration.

**Reference**

[1] Diochnos, D., Mahloujifar, S., & Mahmoody, M. (2018). Adversarial risk and robustness: General definitions and implications for the uniform distribution. In Advances in Neural Information Processing Systems (pp. 10359-10368).<br>
[2] Mahloujifar, S., Diochnos, D. I., & Mahmoody, M. (2019, July). The curse of concentration in robust learning: Evasion and poisoning attacks from concentration of measure. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, pp. 4536-4543).<br>
[3] Mahloujifar, S., Zhang, X., Mahmoody, M., & Evans, D. (2019). Empirically Measuring Concentration: Fundamental Limits on Intrinsic Robustness. To appear in Advances in Neural Information Processing Systems.
