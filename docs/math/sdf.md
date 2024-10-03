---
layout: default
title: SDF / Signed Distance Function/Field
permalink: /signed-distance-function/
parent: Maths
---

# SDF / Signed Distance Function/Field

A **signed distance function (SDF)** is a mathematical function that describes the distance from a point in space to the surface of an object. The function returns a positive value if the point is outside the object, a negative value if the point is inside the object, and zero if the point is on the surface of the object.

the terms **field** and **function** are often used interchangeably, but the term **field** can also refer to pre-computed grid of distances as in the case of Valve's font rendering technique.

## Usage in Computer Graphics

SDFs when combine to ray marching can be used to render complex shapes and scenes in real-time. They are particularly useful for rendering fractals, organic shapes, smooth surfaces, and other geometrically complex objects that are difficult to represent with traditional polygonal meshes.

## Going further

- Inigo Quilez's [article on SDFs](https://iquilezles.org/www/articles/distfunctions/distfunctions.htm)
- [Improved Alpha-Tested Magnification for Vector Textures and Special Effects](https://steamcdn-a.akamaihd.net/apps/valve/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf) - Valve's font rendering technique using SDFs