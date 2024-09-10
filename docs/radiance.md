---
layout: default
title: Radiance
permalink: /radiance/
---

# Radiance

Radiance is a term used in computer graphics to describe the **amount of light energy emitted, reflected, or transmitted by a unit surface or volume** in a scene. It is a fundamental concept in lighting and rendering, as it determines the brightness and color of objects in a virtual environment.

Radiance is typically measured in units of power per unit area per unit solid angle, such as watts per square meter per steradian (W/m²/sr).

As opposed to irradiance, which describes the **total amount of light energy incident on a unit surface**, radiance focuses on the **energy for a given direction**. This is useful as for a given surface, only the light emitted towards the camera contributes to the final image, and radiance helps to quantify this contribution.

## Usage in Computer Graphics

In practice, a unit surface is more often that not a pixel on the screen where the surface appears, and radiance is used to calculate the color of each pixel in the final image. By considering the radiance of light sources, the reflectance properties of surfaces, and the geometry of the scene, rendering algorithms can produce realistic images that simulate the behavior of light in the real world.