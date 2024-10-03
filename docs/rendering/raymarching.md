---
layout: default
title: Ray Marching
permalink: /ray-marching/
parent: Rendering
---

# Ray Marching

**Ray marching** is a rendering technique used to generate images by walking along the path of a ray through a scene. As opposed to [ray tracing](/raytracing/) which computes analytically the intersection of a ray with the geometry, ray marching steps along the ray in small increments, testing for intersections at each step.

Combined with [signed distance functions (SDFs)](/signed-distance-function/), instead of marching in small increments, the ray is marched by a distance defined by the SDF of the nearest object.

## Usage in Computer Graphics

It's the most used technique for rendering fractals, organic shapes, smooth surfaces, and other geometrically complex objects that are difficult to represent with traditional polygonal meshes. A lot of shaders on [Shadertoy](https://www.shadertoy.com/) use it to render complex scenes in real-time using only a fragment shader.

## Going further
- [An introduction to Raymarching](https://www.youtube.com/watch?v=khblXafu7iA) - Kishimisu
- [Inigo Quilez's channel](https://www.youtube.com/@InigoQuilez)