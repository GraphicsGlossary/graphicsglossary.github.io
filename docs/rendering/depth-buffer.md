---
layout: default
title: Depth Buffer / Z-Buffer
permalink: /depth-buffer/
parent: Rendering
---

# Depth Buffer / Z-Buffer

The depth buffer, also known as the Z-buffer, is an array of the size as the screen, which, for each pixel, stores the depth of the closest object to the camera.

It is stored in the same format as the color buffer, with one value per pixel, and is updated during the rendering process. When a new object is drawn, the depth of each pixel is compared to the value in the depth buffer. If the new object is closer to the camera, its depth value is written to the depth buffer, and the color value is written to the color buffer. If the new object is farther away, the depth buffer is left unchanged.

## Usage in Computer Graphics

The depth buffer is used in many rendering algorithms to determine the visibility of objects in a scene. It is typically used in combination with other techniques such as rasterization, shading, and texturing to produce realistic images of 3D scenes.

## Going further