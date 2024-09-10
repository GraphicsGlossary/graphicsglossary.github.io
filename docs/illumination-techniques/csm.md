---
layout: default
title: CSM / Cascaded Shadow Map
permalink: /cascaded-shadow-map/
---

# CSM / Cascaded Shadow Map

A **Shadow Map** consists of casting shadows by rendering the scene from the light's point of view and storing the depth information in a texture. This texture is then used to determine if a pixel is in shadow or not.

**Cascaded Shadow Map (CSM)** is a technique used to cast shadows in real-time applications using shadow maps of varying resolutions depending on the distance from the camera.