---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a condensed matter theorist working on strongly correlated materials and random unitary circuits.


Random Number-Conserving Unitary Circuits
======
[See Paper](publication/2023-random-unitaries)

![image](images/replicas.png)

Random unitaries are valuable primitives in a variety of protocols in quantum information, particularly in randomized benchmarking.
It is impractical to use random global unitary circuits drawn from a uniform measure.
Instead, we may construct *approximate designs* which are good enough for practical purposes.

When the individual circuit elements are restricted by conservation laws, we answer the questions:
1. Do deep random local *number-conserving* circuits approximate their global counterparts?
2. How deep is deep? At what timescale do local circuits converge to global?

We first show that these circuits do indeed converge to the global Haar measure up to very large moments, which is to say "good enough" for all practical purposes.
By mapping the random circuit ensembles to a statistical physics model, we show that convergence is lower bounded by timescales set by low-energy Goldstone modes, $$O(L^2 \log L)$$, only slightly slower than the naive diffusive intuition.


The *All-Pairs* Protocol for Shadow Tomography
======
[See Paper](publication/2024-8-7-shadows)

![image](images/shadows.png)
