---
layout: page
title: Contribute
permalink: /contribute/
---

# Contribute

The Graphics Glossary is a work in progress, and contributions are welcome! If you would like to add a new term, correct an error, or suggest an improvement, please follow the guidelines below.

To contribute, you are encouraged to use the GitHub repository of this project [https://github.com/GraphicsGlossary/graphicsglossary.github.io](https://github.com/GraphicsGlossary/graphicsglossary.github.io) and either create a pull request, open an issue, or use the discussions tab.

## Some guidelines

There no strict rules for contributing, but here are some priorities you should keep in mind when contributing to a term, ordered by importance:
1. **Explanation over strict definition**
2. **Understandable for beginners, useful for everyone**
3. **Clarity over exhaustiveness**
4. **Demistifying technicalities rather than ignoring them**
4. **Visuals are worth thousands words**
5. **Focus on computer graphics over general definitions**
6. **Compensate the lack of exhaustiveness with linked resources**

If don't feel like you can tick all the boxes, don't worry, someone else (probably me) will complete your work. **Contributing a little is better than not contributing at all.**

### 1. Explanation over strict definition

Try to make people click with the term. The goal is to provide a clear explanation of the term in relation to computer graphics, not a wikipedia page.

For example, prefer something like this:

>A **Manifold** is a surface in which every point has a small neighborhood that could be approximated by a flat surface. 

*Source: 'Fundamentals of Computer Graphics' by Peter Shirley and Steve Marschner*

Over something like:

>A **Manifold** is topological space with the property that each point has a neighborhood that is homeomorphic to an open subset of n-dimensional Euclidean space.

*Source: [Wikipedia](https://en.wikipedia.org/wiki/Manifold)*

### 2. Understandable for beginners, useful for everyone

The glossary is not only aimed at beginners, but it should be accessible to most of them. Just keep in mind that people might not have the same background as you.

If you need to refer to other technical terms, try to explain them briefly on the way, even if they are already in the glossary.

Example:

>## CSM / Cascaded Shadow Mapping
>
>A **Shadow Map** consists of rendering shadows by rendering the scene from the light's point of view and storing the depth information in a texture. This texture is then used to determine if a pixel is in shadow or not.
>
>**Cascaded Shadow Mapping (CSM)** casts shadows using shadow maps of varying resolutions depending on the distance from the camera. Shadows on far distances use lower resolution shadow maps, while shadows on close distances use higher resolution.

*The Shadow Map glossary page exists, but it doesn't hurt to repeat a bit of information.*


### 3. Clarity over exhaustiveness

If you can be both exhaustive and clear, that's great! But if you have to choose, prefer clarity. The goal is to make people understand the term, not to make them experts.

### 4. Demistifying technicalities rather than ignoring them

By thinking about beginners, you might fear diving into the mathemathics or the computer science behind a term. I firmly believe that you should not ignore them, but rather explain bit by bit without skipping what you may assume is trivial.

The [Homogeneous Coordinates](/homogeneous-coordinates/) page is, I believe, a good example of this.

### 5. Visuals are worth thousands words

Visuals are a great way to help people understand a concept. It can be an image, a diagram, a small video or even a code snippet. **Please make sure not to use copyrighted material.**

### 6. Focus on computer graphics over general definitions

The glossary is about computer graphics, so try to focus on why the concept is relevant to the field.