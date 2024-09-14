---
layout: default
title: ReSTIR / Reservoir-based Spatio-Temporal Importance Resampling
permalink: /restir/
parent: Illumination Techniques
---

# ReSTIR / Reservoir-based Spatio-Temporal Importance Resampling

**ReSTIR** is a rendering algorithm that computes path tracing with some constraints to achieve real-time rendering. It recycles light computations from previous frames to reduce the number of samples needed to render a scene (Reservoir-based Spatio-Temporal) and focuses the light sampling process where light contribution is the most important (Importance Resampling).

Let's break down the name:

- Re - Reservoir-based:

This refers to the use of reservoir sampling, a statistical technique that maintains a fixed-size collection (or "reservoir") of samples. In ReSTIR, reservoirs are used to store important light samples that contribute significantly to the lighting in a scene. These samples can be reused across different pixels and frames.

- ST - Spatiotemporal:

Spatiotemporal resampling means that ReSTIR reuses samples in both space (across pixels in the image) and time (across frames in an animation or interactive scene). This allows the algorithm to gather more relevant lighting information from both neighboring pixels and previous frames, reducing noise and improving lighting accuracy.

- R - Importance Resampling:

Resampling is the process of drawing new samples from a set of existing ones, based on their importance. In ReSTIR, light paths or samples are resampled based on their contributions to lighting, ensuring that the most relevant samples are retained and reused to improve the overall rendering quality without increasing the computational burden.
Together, ReSTIR utilizes these principles to efficiently manage lighting samples for more accurate and realistic real-time rendering, particularly in complex lighting situations.

## Going further

- Spatiotemporal reservoir resampling for real-time ray tracing with dynamic direct lighting - NVIDIA Research 2020 - [PDF](https://research.nvidia.com/sites/default/files/pubs/2020-07_Spatiotemporal-reservoir-resampling/ReSTIR.pdf)
- [A Gentle Introduction to ReSTIR](https://interplayoflight.wordpress.com/2023/12/17/a-gentler-introduction-to-restir/) - Interplay of Light Blog
- A Gentle Introduction to ReSTIR: Path Reuse in Real-time - SIGGRAPH 2023 Course - [Site](https://intro-to-restir.cwyman.org/) - [PDF & Video](https://dl.acm.org/doi/10.1145/3587423.3595511)