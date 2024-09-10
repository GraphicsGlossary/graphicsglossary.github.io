---
layout: default
title: Meshlet
permalink: /meshlet/
---

# Meshlet

A **Meshlet** is a small subdivision of a mesh that is small enough to fit in size for the mesh shaders stage of rendering pipelines.

## Usage in Computer Graphics

The usual way of computing shaders on meshes is to process each vertices independently, which can lead to a lot of redundant computation as vertices' attributes might be repeated by all the other vertices in the mesh. But GPUs allow multiple threads of the same work group to share some data, which can be exploited to process whole meshlets in a single work group of threads.

Meshlets extracted from meshes are designed to fit in the memory size of a single work group, which allows the GPU to process them in parallel. This can lead to a significant performance improvement compared to processing each vertex independently.