---
layout: default
title: Radiosity
permalink: /radiosity/
---

# Radiosity

**Radiosity** is a global illumination algorithm that simulates diffuse reflection and emission of light between surfaces in a scene.

The technique divides the scene into small patches and computes the amount of light that is reflected between each pair of patches. The algorithm is based on the principle of energy conservation, which states that the total amount of light energy in a closed system remains constant.

It simplifies the rendering equation by considering every surface to be exclusively diffusing or emitting light. This means that for a unit surface area, the amount of light reflected or emitted is the same in all directions.

The term "radiosity" comes from the field of radiometry and originally refers to the total amount of light power exiting a surface in all directions.

## Usage in Computer Graphics

Radiosity is used in the context of offline rendering to produce high-quality images with realistic lighting effects. The algorithm is particularly well-suited for scenes with diffuse surfaces, such as architectural interiors, where indirect lighting plays a significant role in the overall appearance of the scene.

It's also used by Valve's Source Engine to precompute lighting information for static scenes.

## Going further

- Radiosity a programmer's perspective [PDF](https://www.researchgate.net/profile/Ian-Ashdown/publication/220690300_Radiosity_-_a_programmer%27s_perspective/links/0912f4ff5f5eb42776000000/Radiosity-a-programmers-perspective.pdf)
- Radiosity and Realistic Image Synthesis [PDF](http://twanclik.free.fr/electricity/electronic/pdfdone12/Radiosity%20and%20realistic%20image%20synthesis%20Cohen%20M.F.,%20Wallace%20J.R.%20(AP,%201995)(412s).pdf) - [Book](https://www.amazon.com/Radiosity-Realistic-Image-Synthesis-Michael/dp/0121782700)
- [Valve Radiosity simulation (RAD)](https://developer.valvesoftware.com/wiki/RAD_(technical))