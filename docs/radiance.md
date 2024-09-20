---
layout: default
title: Radiance
permalink: /radiance/
---

# Radiance

**Radiance** generally refers to the amount of light that is entering or leaving a unit surface each unit time for a given direction. 

It's a physical quantity measured in Watts (light power) per square meter (unit surface) per steradians (3d direction) : W/m²/sr.

## Usage in Computer Graphics

It's mostly used in Physically Based Rendering (PBR) where the focus is representing light flow with physics models.

As opposed to **irradiance**, which is the amount of light entering a surface in every direction, radiance is directional. Thus, it is quite useful as only the light emitted towards the camera contributes to the final image.

In practice, a *unit surface* is more often that not a pixel on the screen that covers a surface, and radiance is then used to calculate the color of each pixel in the final image. By considering the radiance of light sources, the reflectance properties of surfaces, and the geometry of the scene, rendering algorithms can produce realistic images that approximate the behavior of light in the real world.

## Going further

[PBRT 4th Edition - Radiometry](https://pbr-book.org/4ed/Radiometry,_Spectra,_and_Color/Radiometry) 
