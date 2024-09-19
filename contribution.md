---
layout: page
title: Contribute
permalink: /contribute/
---

# Contribute

The Graphics Glossary is a work in progress, and contributions are welcome! If you would like to add a new term, correct an error, or suggest an improvement, please follow the guidelines below.

To contribute, you are encouraged to use the GitHub repository ( [https://github.com/GraphicsGlossary/graphicsglossary.github.io](https://github.com/GraphicsGlossary/graphicsglossary.github.io) ) and either create a pull request, open an issue, or use the discussions tab.

You can also use my [social media](https://x.com/Miolith_) if you prefer suggesting modifications privately.

## Some guidelines

There are no strict rules for this, but here are some priorities you should keep in mind when contributing to a term, ordered by importance:
1. **Explanation over strict definition**
2. **Understandable for beginners, useful for everyone**
3. **Clarity over exhaustiveness**
4. **Demistifying technicalities rather than ignoring them**
4. **Visuals are worth thousands words**
5. **Focus on computer graphics over general definitions**
6. **Compensate the lack of exhaustiveness with linked resources**

If you don't feel like you can tick all the boxes, don't worry, someone else will complete your work. **Contributing a little is better than not contributing at all.**

### 1. Explanation over strict definition

Try to make people click with the term. The goal is to provide a clear explanation of the term in relation to computer graphics, not a wikipedia page.

For example, prefer something like this:

>A **Manifold** is a surface in which every point has a small neighborhood that could be approximated by a flat surface. 

<small>*Source: 'Fundamentals of Computer Graphics' by Peter Shirley and Steve Marschner*</small>

Over something like:

>A **Manifold** is topological space with the property that each point has a neighborhood that is homeomorphic to an open subset of n-dimensional Euclidean space.

<small>*Source: [Wikipedia](https://en.wikipedia.org/wiki/Manifold)*</small>

If you ever go for the latter, at least try to quickly explain the technical terms.

### 2. Understandable for beginners, useful for everyone

The glossary is not only aimed at beginners, but it should be accessible to most of them. Just keep in mind that people might not have the same background as you.

If you need to refer to other technical terms, try to explain them briefly on the way, even if they are already in the glossary.

Example:

>## Sparse Octree
>An **octree** is a tree data structure where each node has 0 or 8 children generally used to divide a volume into 8 sub-volumes. A **Sparse Octree** is an octree where only nodes containing data are stored, and empty nodes are not allocated in memory.

<small>*The octree page already exists, but it doen't hurt to repeat a bit of information here.*</small>


### 3. Clarity over exhaustiveness

If you can be both exhaustive and clear, that's great! But if you have to choose, prefer clarity. The goal is to make people understand the term, not to make them experts.

### 4. Demistifying technicalities rather than ignoring them

By thinking about beginners, you might fear diving into the mathemathics or the computer science behind a term. I firmly believe that you should not ignore them, but rather explain bit by bit without skipping what you may assume is trivial.

The [Homogeneous Coordinates](/homogeneous-coordinates/) page is, I believe, a good example of this.

### 5. Visuals are worth thousands words

Visuals are a great way to help people understand a concept. It can be an image, a diagram, a small video or even a code snippet.

### 6. Focus on computer graphics over general definitions

The glossary is about computer graphics, so try to focus on why the concept is relevant to the field.

### 7. Compensate the lack of exhaustiveness with linked resources

As you cannot develop every detail of the concept, try to provide links to resources that you believe to be valuable to gain working knowledge of the concept.
