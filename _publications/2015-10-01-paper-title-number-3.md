---
title: "Optimal Primal-Dual Algorithm with Last iterate Convergence Guarantees for Stochastic Convex Optimization Problems"
collection: publications
category: manuscripts
permalink: /publication/last-iterate
excerpt: 'This paper is under first revision'
date: 2024-10-24
venue: 'arXiv'
paperurl: 'http://mohammadkhf.github.io/files/lastiterate.pdf'
citation: 'D Boob, M Khalafi - arXiv preprint arXiv:2410.18513, 2024'
---

This paper introduces a novel first-order algorithm for solving composite nonsmooth and stochastic convex optimization problems with function constraints. While most existing methods focus on convergence guarantees for the average-iterate solution, there is increasing interest in last-iterate convergence due to its practical advantages, such as sparsity, privacy, and improved empirical performance.

We present the Augmented Constraint Extrapolation (Aug-ConEx) method, the first algorithm to achieve the best-known convergence rates for last-iterate solutions in this setting. Built on the augmented Lagrangian framework, Aug-ConEx employs a novel linearized constraint approximation. It achieves an optimal convergence rate in nonsmooth stochastic settings and an improved rate for strongly convex objectives. Additionally, it accelerates convergence based on Lipschitz smoothness constants without extra complexity factors.

To the best of our knowledge, this is the first method to establish such differentiated last-iterate guarantees for composite nonsmooth stochastic optimization. We validate its effectiveness through numerical comparisons with state-of-the-art algorithms.
