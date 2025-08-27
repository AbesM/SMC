+++
title = 'Baykur-Hamada'
date = 2025-06-17
lastmod = ':git'
+++


The main results of the paper are: 

1. Every closed, connected, nonorientable 4–manifold X admits a simplified broken Lefschetz fibration that can be obtained by homotoping a given generic map $X\mapsto S2$.

This builds on some work of Baykur Saeki

2. Every closed, connected, nonorientable 4–manifold admits a simplified trisection.

3. They get sort of a classification of low genera fibration. Key fact: SBLF don't have constant genus fiber.

4. Theorem 4. Every closed, connected, nonorientable 4–manifold can be obtained by surgery along a link of tori in Z = a (S2 × RP2)#b RP4#c CP2#d (S1 × S3), for some a, b, c, d ∈ Z≥0. This is similar to a theorem of Iwase (and should remind of the exercise from R?)


# Preliminaries

We care for three kinds of singularities
1. Lefschetz Singularities 
2. Fold singularity $(t,x_1,x_2,x_3)\mapsto (t, \pm x_1^2\pm x_2^2\pm x_3^2)$ 
3. Cusp singularity $ (t,x_1,x_2,x_3)\mapsto (t,x_1^3+tx_1\pm x_2^2\pm x_3^2)$

It is due to Whitney that maps from a 4-manifold to a surface with only folds and cusps are generic in the smooth maps endowed with the Whitney topology. The singular set are an embedded 1-manifold in X.

Given a map with singularities as above we can describe it as a base diagram on $\Sigma$. Check the paper for the rules.

# SBLF

We will work with the following definition. A SBLF $f:X\to S^2$ is a BLF such that:
1. f is injective on $C_f \cup Z_f$
2. $Z_f$ is connected
3. all fibers are connected, 
4. f($C_f$) lies on the higher genus side. 

# Simplified Trisection 

A $(g,k)$ trisection of $X$ is a decomposition $X=X_1\cup X_2 \cup X_3$ where each $X_i$ a 4-handlebody, they have pairwise intersection in 3-handlebody and triple intersection along a central surface.