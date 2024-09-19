---
layout: default
title: MSAA / Multisample Anti-Aliasing
permalink: /multisample-anti-aliasing/
---

# MSAA / Multisample Anti-Aliasing

**Anti-aliasing** is the task of reducing jaggies or stair-stepping artifacts in images by smoothing out the edges of objects. It's a common problem in computer graphics, especially when rendering images at lower resolutions.

While some techniques consists of rendering the scene at a higher resolution and then downscaling it to the desired resolution, **Multisample Anti-Aliasing (MSAA)** renders directly at the desired resolution and try instead to use a higher resolution depth/stencil buffers to determine how much the pixel is covered by the geometry. The coverage information is then used to blend the pixel color with the background color.
