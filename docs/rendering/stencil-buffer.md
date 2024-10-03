---
layout: default
title: Stencil Buffer
permalink: /stencil-buffer/
parent: Rendering
---

# Stencil Buffer

The **stencil buffer** is a per-pixel buffer that stores integer values used for masking and clipping operations in the rendering pipeline.

It's up to the application to store any desired value in the stencil buffer, which can then be used in the stencil test to determine whether a pixel should be discarded or not.