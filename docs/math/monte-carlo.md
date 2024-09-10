---
layout: default
title: Monte Carlo
permalink: /monte-carlo/
parent: Maths
---

# Monte Carlo

**Monte Carlo** methods are a class of algorithms that use random sampling to estimate numerical results.

For example, an integral could be numerically computed either by summing every point in the domain by a small step (Riemann sum), or by summing the values of the function at random points in the domain and then averaging the results. The more samples taken, the more accurate the estimate will be.

## Usage in Computer Graphics

Typical use of Monte Carlo is in path tracing, where it is used to estimate the integral of the rendering equation. This is done by sampling the scene multiple times and averaging the results to produce a final image.

## Going further

- [PBRT 4th edition - Monte Carlo Integration](https://www.pbr-book.org/4ed/Monte_Carlo_Integration/Monte_Carlo_Basics)
