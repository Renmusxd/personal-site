---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a condensed matter theorist working on strongly correlated materials and random unitary circuits, with a focus on emergent statistical models and understanding physics through the lens of computation.


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

Random measurement protocols have proven themselves to be useful tools for nascent quantum hardware.
These protocols can efficiently benchmark new platforms, allowing, for example, designers to demonstrate that the hardware is behaving as expected and is ready to perform computation.
*Classical Shadows* are a new family of such protocols which have an additional benefit: they data they gather can be used to answer questions about the hardware we don't yet know to ask.
In other words the data is, in some sense, basis agnostic: "Measure first, ask questions later".

These protocols are surprisingly efficient: Using the *local* protocol, with only a handful of measurements we can start to reconstruct expectation values for any low-weight observables.
We extend these protocols to systems with conservation laws, such as quantum simulation platforms of ultracold atoms, and design reconstruction algorithms which are exponentially more efficient than was possible with previous studies.


