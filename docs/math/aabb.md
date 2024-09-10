---
layout: default
title: AABB / Axis-Aligned Bounding Box
permalink: /axis-aligned-bounding-box/
parent: Maths
---

# AABB / Axis-Aligned Bounding Box

An Axis-Aligned Bounding Box (AABB) is a simple rectangular box that is parallel to the coordinate axes. It is defined by two points, the minimum and maximum extents of the box, which represent the corners of the box in 3D space.

## Usage in Computer Graphics

- Collision detection: AABBs are commonly used in collision detection algorithms to quickly determine if two objects are intersecting. The algorithm is simple and efficient, making it a popular choice for real-time applications.
- Visualization: AABBs are often used to represent the approximate size and shape of more complex objects in a scene. They are easy to calculate and render, making them a useful tool for debugging and optimization.
- Spatial partitioning: AABBs are used in spatial partitioning techniques such as bounding volume hierarchies (BVH) and octrees to divide space into smaller regions for efficient culling and traversal of objects.