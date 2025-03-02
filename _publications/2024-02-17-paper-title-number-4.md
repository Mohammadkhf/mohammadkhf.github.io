---
title: "Accelerated Primal-Dual Methods for Convex-Strongly-Concave Saddle Point Problems"
collection: publications
category: conferences
permalink: /publication/ICML
excerpt: 'This paper was published in my first year of PhD'
date: 2023-6-12
venue: 'International Conference on Machine Learning (ICML)'
paperurl: 'http://mohammadkhf.github.io/files/icml.pdf'
citation: 'M Khalafi, D Boob - International conference on machine learning, 2023'
---

We study a primal-dual (PD) method for saddle point problems (SPP) that replaces the standard proximal step with a linear approximation of the primal function, leading to a Linearized Primal-Dual (LPD) method. For convex-strongly concave SPPs, we find that LPD has a suboptimal dependence on the Lipschitz constant of the primal function.

To address this, we integrate features of Accelerated Gradient Descent into LPD, resulting in the Accelerated Linearized Primal-Dual (ALPD) method, which achieves optimal gradient complexity for SPPs with semi-linear coupling functions. For more general nonlinear coupling functions, we introduce an inexact ALPD method, which maintains optimal primal gradient evaluations while significantly reducing the complexity of the coupling term.

We validate our theoretical results through numerical experiments on QCQPs with different rules of regularizations.
