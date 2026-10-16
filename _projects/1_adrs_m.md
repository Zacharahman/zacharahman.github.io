---
layout: page
title: ADRS-M
description: Accelerated Douglas–Rachford splitting via monotone residual restart
img:
importance: 1
category: research
---

**Accelerated Douglas–Rachford Splitting via Monotone Residual Restart**
Course research project, Iterative Methods, Courant Institute, NYU (Spring 2026), with Gabriel Abreu.

Inertial acceleration speeds up operator-splitting methods in practice but can destroy the monotonicity guarantees that make them reliable. ADRS-M addresses this with a restart rule that selects between the inertial and standard step based on the fixed-point residual.

### Contributions

- Proposed **ADRS-M**, an inertial Douglas–Rachford method for nonsmooth convex problems that picks the inertial or standard step by fixed-point residual.
- Proved a monitor inequality guaranteeing a **nonincreasing residual**, via firm nonexpansiveness and Fejér monotonicity.
- Benchmarked on LASSO, elastic net, basis pursuit, and nuclear norm problems (SVD thresholding, projections, least-squares solves).

### Results

The method required **30–79% fewer iterations** than standard DRS on three of four problem families, and was never slower on the fourth.
