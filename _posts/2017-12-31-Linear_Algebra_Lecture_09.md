---
layout:     post
title:      Lecture 09 (Linear Algebra)
subtitle:   
date:       2017-12-31
author:     Sun Yin
header-img: img/tags_linearAlgebra.png
catalog: true
tags:
    - Linear Algebra
---
## Lecture 09

**1. Linear Independent**

**2. Span Space**

**3. Basis**

**4. Dimension**

---

### 1. Linear Independence

**N(A) when m<n**

Suppor a matrix with m by n and m<n, then there must be non zero vectors in N(A), because is has one or more free varibles.

**Definition**

Vectors$$\quad { X }_{ 1 },{ X }_{ 2 },......,{ X }_{ n }\quad$$ are independent if no combination gives zero vector(except zero combination).

$$
{ c }_{ 1 }{ X }_{ 1 }+{ c }_{ 2 }{ X }_{ 2 }+......+{ c }_{ N }{ X }_{ n }\neq 0
$$

**Comparison**

$${ V }_{ 1 },{ V }_{ 2 },......,{ V }_{ N }$$ are column vectors of matrix A.



They are **independent** if: The nullspace of A is { zero vector} $$\Leftrightarrow$$ No free variables $$\Leftrightarrow$$ rank=N 

They are **dependent** if: There are nonzero vector that make Av=0 $$\Leftrightarrow$$ Having free variables$$\Leftrightarrow$$ rank<N

### 2. Span Space

$$Vectors\quad { V }_{ 1 },{ V }_{ 2 },......,{ V }_{ N }\quad$$ span a space means: this space consists of all combinations of the vectors.

### 3. Basis

**Definition**

$$Basis\quad for\quad a\quad space\quad is\quad a\quad set\quad of\quad vectors\quad with\quad 2\quad properties\quad below:$$

* They are linear independent.
* The vectors span the space.

**Basis of \\({R}^{N}\\)**

N vectors is basis for \\({R}^{N}\\) space if the N by N matrix with these vectors as columns is invertible.

### 4.Dimension

**Definition**

Every Basis for a space has the same number of vectors, that's the dimension of the space.

**Example**

$$
A=\begin{bmatrix} 1 & 2 & 3 & 1 \\ 1 & 1 & 2 & 1 \\ 1 & 2 & 3 & 1 \end{bmatrix}
$$

2 = the rank of A = the number of pivots of A = **dimension of C(A)**

4 = n - 2 = the number of free variables = **dimension of N(A)**


