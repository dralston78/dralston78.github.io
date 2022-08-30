---
layout: page
title: Stochastic Neighborhood Embedding
description: 
img: /assets/img/unrolled_sr_umap.jpg
importance: 1
category: projects
---

This project focused on the underlying similarities of the t-SNE and UMAP algorithms for nonlinear dimension reduction.  t-SNE (t distrubtion stochastic neighborhood embedding) was first released by van der Marteen et. all in 2008; UMAP was released a decade later in 2018 by McGinnes et. all.  Unsprisingly, UMAP generally performs better, both with global and local embeddings, as well as having far superior performance.  What was most interesting to me was the mathematial commonality behind the two algorithms, despite the large diffeerences in how they were framed.  In particular, the authors of t-SNE used techniques from probabilty, stochastics, and information theory to motivate their process, whereas the authors of UMAP appealed to graph theory and topology.  In addition to comparing the algorthims' mathematical underpinnings, I wrote (from the ground up) a basic implementation of stochastic neighborhood embedding, the general technique both processes are based on.  

- [Report](/assets/pdf/tSNE_UMAP.pdf)
- [GitHub Repository](https://github.com/dralston78/stochastic-neighborhood-embedding/)
