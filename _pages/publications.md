---
layout: archive
title: "Select publications and preprints (by topic)"
permalink: /publications/
author_profile: true

---

{% include base_path %}

For a complete list of publications, please refer to [my CV](https://RuobinGong.github.io/files/RG-cv.pdf).

## On inference foundations

{% for post in site.publications_foundation reversed %}
  {% include archive-single.html %}
{% endfor %}

## On statistical privacy

{% for post in site.publications_privacy reversed %}
  {% include archive-single.html %}
{% endfor %}

## Data science and related topics

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



