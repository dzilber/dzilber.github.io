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
* Ph.D in Statistics, Texas A&M University, 2021
* M.S. in Management Science and Engineering, Stanford University, 2012
* B.S. in Mathematics, University of North Carolina at Chapel Hill, 2010

Work experience
======
* 2012-2016: Operations Research Analyst
  * Reddwerks
  * Duties included: developing warehouse control algorithms in Java
  * Supervisor: Arturo Hinojosa
  
Skills
======
* Bayesian hierarchical modeling
  * Implementation of MCMC (manual, STAN, nimble)
  * Large spatial data: Vecchia approximations with Gaussian Processes
  * Variational Methods
* Frequentist statistic analysis
  * Penalized optimization with gradient or proximal methods
  * Constrained convex optimization
* So many other skills

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
* Mentoring summer interns
