---
layout: default
title: Homogeneous Coordinates
permalink: /homogeneous-coordinates/
---

# Homogeneous Coordinates

Homogeneous coordinates consist of adding an extra coordinate *w* to the usual Cartesian coordinates *x*, *y*, and *z*.

This works as follows:

- the 3D vector $$(x, y, z)$$ becomes $$(x, y, z, 1)$$
- $$(x, y, z, w)$$ is equivalent in Cartesian coordinates to $$(\frac{x}{w}, \frac{y}{w}, \frac{z}{w})$$.
- $$(x, y, z, 0)$$ is equivalent to a point at infinity.

Homogeneous coordinates are used in computer graphics to simplify the representation of transformations, typically translations and projections. They allow these transformations to be represented as matrix multiplications, which can be more easily combined and applied to points and vectors.

For example, a translation, usually done with :\
$$
(x, y) + (t_x, t_y) = (x + t_x, y + t_y)
$$\
can be represented in homogeneous coordinates as:\
$$
\begin{bmatrix} 1 & 0 & t_x \\ 0 & 1 & t_y \\ 0 & 0 & 1 \end{bmatrix} \times (x, y, 1) = (x + t_x, y + t_y, 1)
$$

Similarly, a perspective projection, usually done with:\
$$
(x, y, z) \rightarrow (\frac{f \cdot x}{z}, \frac{f \cdot y}{z}, f)
$$\
can be represented in homogeneous coordinates as:\
$$
\begin{bmatrix}
f & 0 & 0 & 0 \\
0 & f & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 1 & 0
\end{bmatrix} \times (x, y, z, 1) = (\frac{f \cdot x}{z}, \frac{f \cdot y}{z}, f, 1)
$$
*f* being the focal length of the camera.

This offers a way to combine every transformations in a single matrix by multiplying them together, which can be then multiplied to a point or a vector to apply all the transformations at once.

## Usage in Computer Graphics

- Projecting an object from one space to another with a single matrix, such as from local space to world space.
- Projecting a 3D object to a 2D screen space.
- Setting $$w = 0$$ to represent purely directional vectors (such as normals) as this disables translation.

## Going further

- [Quick Understanding of Homogeneous Coordinates for Computer Graphics - Miolith - 2023](https://www.youtube.com/watch?v=o-xwmTODTUI)
- [Triangle Scan Conversion using 2D Homogeneous Coordinates - 1997](https://www.cs.cmu.edu/afs/cs/academic/class/15869-f11/www/readings/olano97_homogeneous.pdf)