---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Physics, Boston University, 2025 (expected)
* B.S. in Physics and Computer Science, Cornell University 2017

Work experience
======
* PhD Program (Laumann Group), Boston University Boston, MA  August 2019 – Present
  * Research includes Highly Frustrated Magnets, Randomized Measurement Protocols, Gauge Theories on a Lattice
  * Used Quantum Annealer to study quantum dimer models and compare to custom Quantum Monte Carlo implementation.
* Google LLC, Mountain View, CA August 2017 – August 2019
  * Employed as Software Engineer in the Search Quality Department developing Machine Learning models for NLP.
  * Work included large-scale data analysis and writing high performance code for serving queries.
* Laboratory for Elementary Particle Physics (Rubin Group), Cornell University, Ithaca, NY  December 2013 - May 2017
  * Developed Python and Fortran libraries to simulate and analyze electron cloud dynamics for Cornell’s particle accelerator. 
  * Operated accelerator and logged data for related experiments.
* UCSF Laboratory Internship (Blackburn Group), San Francisco, CA April 2011 - 2013
  * Data analysis genetic data for research on telomere regenerative processes and correlating health and lifespan in yeast.  
  * Programmed a robotic DNA sequencer for telomere analysis for a prospective study on patient health for a large HMO.

  
Skills
======
* Programming Languages 
  * Proficient in Rust (5yrs), Python (17yrs), C++ (10yrs), Java (10yrs)
  * Familiar with: Julia, Fortran, Haskell, OCaml, Kotlin, Matlab, Swift 
* GPU Programming
  * WGPU and CUDA
  * Monte carlo sampling
* Machine Learning
  * Naural Language Processing (More RNNs than LLMs)
  * Unsupervised learning
* Large projects
  * Quantum Monte Carlo SSE library for small-field qubit models.
  * Wrote a custom compiler for an object oriented language from scratch
  * Designed a quantum circuit simulation library in Rust

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
