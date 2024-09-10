---
layout: default
title: NeRF / Neural Radiance Fields
permalink: /neural-radiance-fields/
parent: Rendering
---

# NeRF / Neural Radiance Fields

**Neural Radiance Fields (NeRF)** is a technique that reconstructs a 3D render from a set of 2D pictures of the scene taken from different viewpoints. It uses a neural network to render the scene by predicting the color and opacity of each point and a given direction in the 3D space.

The neural network is exclusively trained on the 2D images of the scene to overfit the data and learn the 3D structure of the scene.

The trained model can now be used to render the scene from any viewpoint by casting rays from the camera and predicting the color and opacity of the points along the ray.

## Going further

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934) by Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng