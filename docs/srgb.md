---
layout: default
title: sRGB
permalink: /srgb/
---

# sRGB

**sRGB** is the standard color space for most consumer electronic devices, such as monitors, digital cameras, and printers. sRGB is a small color space, meaning that it can only represent a limited range of colors compared to other color spaces like Adobe RGB or ProPhoto RGB. However, sRGB is widely used because it is well-supported by most devices and software.

The sRGB space is defined by 3 primary colors: red, green, and blue picked at the wavelengths of 700 nm, 546.1 nm, and 435.8 nm, respectively. These colors are mixed in different proportions to create a wide range of colors.

The space is nonlinear, meaning that the intensity of the colors is not linearly related to the values stored in the image file. In other words, drawing a gradient from white to black won't place the perfect mid grey color at the middle of the gradient, but closer to the black end.

This nonlinearity is designed to match the way the human eye perceives light. The sRGB space uses a gamma correction of 2.2 to encode the intensity of the colors.