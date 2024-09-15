---
layout: default
title: Homogeneous Coordinates
permalink: /homogeneous-coordinates/
---

# Homogeneous Coordinates

**Homogeneous coordinates** consist of adding an extra coordinate *w* to the usual Cartesian coordinates *x*, *y*, and *z*.

This works as follows:

- the 3D vector $$(x, y, z)$$ becomes $$(x, y, z, 1)$$
- $$(x, y, z, w)$$ is equivalent in Cartesian coordinates to $$(\frac{x}{w}, \frac{y}{w}, \frac{z}{w})$$.
- $$(x, y, z, 0)$$ is equivalent to a point at infinity.

This is used in computer graphics to simplify the representation of transformations, typically translations and projections. They allow these transformations to be represented as matrix multiplications, which can be more easily combined and applied to points and vectors.

For example, a translation, usually done with :

$$
(x, y) + (t_x, t_y) = (x + t_x, y + t_y)
$$

can be represented in homogeneous coordinates as:

$$
\begin{bmatrix}
1 & 0 & t_x \\
0 & 1 & t_y \\
0 & 0 & 1
\end{bmatrix}
\times
\begin{bmatrix}
x \\
y \\
1
\end{bmatrix}
=
\begin{bmatrix}
x + t_x \\
y + t_y \\
1
\end{bmatrix}
$$

Similarly, a perspective projection for a 90° field of view, usually done with:

$$
(x, y, z) \rightarrow (\frac{x}{z}, \frac{y}{z})
$$

can be represented in homogeneous coordinates as:

$$
\begin{bmatrix}
1 & 0 & 0 & 0 \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 1 & 0
\end{bmatrix}
\times
\begin{bmatrix}
x \\
y \\
z \\
1
\end{bmatrix}
=
\begin{bmatrix}
x \\
y \\
z \\
z
\end{bmatrix}
=
\begin{bmatrix}
\frac{x}{z} \\
\frac{y}{z} \\
1 \\
1
\end{bmatrix}
$$

This offers a way to combine every transformations in a single matrix by multiplying them together, which can be then multiplied to a point or a vector to apply all the transformations at once.

## Usage in Computer Graphics

- Projecting an object from one space to another with a single matrix, such as from local space to world space.
- Projecting a 3D object to a 2D screen space.
- Setting $$w = 0$$ to represent purely directional vectors (such as normals) as this disables translation.

## Going further

- [Quick Understanding of Homogeneous Coordinates for Computer Graphics - Miolith - 2023](https://www.youtube.com/watch?v=o-xwmTODTUI)