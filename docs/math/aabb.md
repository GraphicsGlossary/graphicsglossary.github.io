---
layout: default
title: AABB / Axis-Aligned Bounding Box
permalink: /axis-aligned-bounding-box/
parent: Maths
---

# AABB / Axis-Aligned Bounding Box

**An Axis-Aligned Bounding Box** (AABB) is a simple rectangular box that is parallel to the coordinate axes. It's generally bounding a set of points in 2D or 3D space.

There are multiple ways to represent an AABB :
- As two points, each being opposites corner of the box.
- As a center point and half-extents, which represent the center of the box and the distance from the center to the edges along each axis.
- A corner point and the widths of the box along each axis.

## Usage in Computer Graphics

- Collision detection: AABBs are commonly used in collision detection algorithms to roughly determine if two objects are intersecting. 

- Visualization: AABBs are often used to represent the approximate size and shape of more complex objects in a scene. They are easy to calculate and render, making them a useful tool for debugging.

- Object detection: In computer vision and image processing, AABBs are used to represent the bounding boxes of objects in an image. They can be used to localize objects and extract features for object recognition and classification.

- Spatial partitioning: AABBs are used in spatial partitioning techniques such as bounding volume hierarchies (BVH) and octrees to divide space into smaller regions for efficient culling and traversal of objects.

## Going further
