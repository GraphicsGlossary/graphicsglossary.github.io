---
layout: default
title: Radiance
permalink: /radiance/
---

# Radiance

**Radiance** generally refers to the amount of light that is entering or leaving a unit surface each unit time for a given direction. 

It's a physical quantity measured in watts (light power) per square meter (unit surface) per steradians (direction) : W/m²/sr.

## Usage in Computer Graphics

It's mostly used in Physically Based Rendering (PBR) where representing light flow with physics models is important.

As opposed to **irradiance**, which is the amount of light that is incident on a surface in every direction, radiance is directional. Thus, it is useful as for a given surface, only the light emitted towards the camera contributes to the final image.

In practice, a *unit surface* is more often that not a pixel on the screen where the surface appears, and radiance is used to calculate the color of each pixel in the final image. By considering the radiance of light sources, the reflectance properties of surfaces, and the geometry of the scene, rendering algorithms can produce realistic images that simulate the behavior of light in the real world.

