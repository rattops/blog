---
layout: post
title: lifting property
category: Category Theory
tags:
  - lifting
  - algebraic-topology
  - homotopy
math: true
toc: true
---
## Formal definition
A pair of morphisms ${ (i,p) }$ has the **lifting property** iff there is a diagonal morphism h for each pair of morphisms ${ (f,g) }$ making the following diagram commutes.

<p align="middle"><iframe class="quiver-embed" src="https://q.uiver.app/#q=WzAsNCxbMCwwLCJBIl0sWzEsMSwiWSJdLFsxLDAsIlgiXSxbMCwxLCJCIl0sWzIsMSwicCJdLFswLDMsImkiLDJdLFswLDIsImYiXSxbMywxLCJnIiwyXSxbMywyLCJoIiwxLHsic3R5bGUiOnsiYm9keSI6eyJuYW1lIjoiZGFzaGVkIn19fV1d&embed" width="304" height="304" style="border-radius: 8px; border: none;"></iframe></p>

Then ${ i }$ has the left lifting property w.r.t. ${ p }$ and ${ p }$ has the right lifting property w.r.t. ${ i }$, denote those ${ i \perp p }$ or ${ i \downarrow p }$.

## Orthogonal with respect to a class
For a class ${ C }$ of morphisms in a category, the left orthogonal w.r.t. C is defined by
$$ C^{\perp l} := \{ \, i \, \mid \, \forall p \in C, i\perp p \, \} $$
and the right orthogonal w.r.t. C is defined by
$$ C^{\perp r} := \{ \, i \, \mid \, \forall p \in C, i\perp p \, \} $$