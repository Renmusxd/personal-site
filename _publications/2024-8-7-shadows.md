---
title: "Efficient Local Classical Shadow Tomography with Number Conservation"
collection: publications
category: manuscripts
permalink: /publication/2024-8-7-shadows
excerpt: 'We propose and analyze a new local shadow protocol adapted to number-conserving systems.'
date: 2023-8-7
venue: 'PRL'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1103/PhysRevLett.133.060802'
citation: 'Sumner N. Hearth, Michael O. Flynn, Anushya Chandran, and Chris R. Laumann <i>Phys. Rev. Lett. 133, 060802</i>'
---

Shadow tomography aims to build a classical description of a quantum state from a sequence of simple random measurements. Physical observables are then reconstructed from the resulting classical shadow. Shadow protocols which use single-body random measurements are simple to implement and capture few-body observables efficiently, but do not apply to systems with fundamental number conservation laws, such as ultracold atoms. We address this shortcoming by proposing and analyzing a new local shadow protocol adapted to such systems. The "All-Pairs" protocol requires one layer of two-body gates and only poly(V) samples to reconstruct arbitrary few body observables. Moreover, by exploiting the permutation symmetry of the protocol, we derive a linear time post-processing algorithm. We provide a proof-of-principle reference implementation and demonstrate the reconstruction of 2- and 4-point functions in a paired Luttinger liquid of hardcore bosons.