---
permalink: /
title: ""
excerpt: "Home"
author_profile: true
redirect_from:
  - /home/
  - /home.html
---


I'm an Assistant Professor of Statistics at [Rutgers University](https://statistics.rutgers.edu/). My research interests lie at the foundations of uncertainty reasoning, Bayesian and generalized Bayesian methodology and computation, in particular random sets, imprecise probability, and Dempster-Shafer theory of belief function, as well as applications to robustness and privacy statistics.



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
