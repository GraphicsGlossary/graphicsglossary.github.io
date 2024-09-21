---
layout: default
title: Ray Tracing
permalink: /ray-tracing/
parent: Rendering
---

# Ray Tracing

**Ray tracing** is a rendering technique that retraces the trajectory of light rays that reach the camera. For each pixel of the image, a ray is cast from the camera through the pixel and into the scene. The ray is then tested for intersection for all objects in the scene. If an intersection is found, the algorithm computes the contribution of the surface to the color of the pixel, and makes the light ray bounce off the surface to simulate reflections, refractions, and shadows.