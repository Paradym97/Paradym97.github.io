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
* Ph.D. in Physical Oceanography, Ocean University of China, 2026 (expected)
* M.S. in Physical Oceanography, Ocean University of China
* B.S. in Marine Science, Ocean University of China

Research Experience
======
* Ph.D. Researcher 
  * Ocean University of China
  * Focus: Investigating mesoscale air-sea interaction and ocean heat uptake in the context of global warming using Earth system models. Developing the Hybrid Coupled Regional Ocean Modeling System (HC-ROMS).
  * Supervisor: Prof. Zhao Jing

* Master's Researcher
  * Ocean University of China
  * Focus: Parameterization of wind-driven turbulent vertical mixing and analyzing the role of global cyclonic/anticyclonic eddies in regulating near-inertial internal waves using eddy-resolving climate models.
  * Supervisor: Prof. Zhao Jing
  
Skills
======
* Numerical Models
  * CESM
  * ROMS
  * HC-ROMS (Developer)
* Programming & Parallel Computing
  * Python
  * Fortran
  * C
  * MPI
  * Julia

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations & Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>