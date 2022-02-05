---
layout: archive
title: ""
permalink: /publications/
author_profile: true

---

[My Google Scholar profile](https://scholar.google.com/citations?user=8W4eh2UAAAAJ&hl=en)

{% include base_path %}

## Inference Foundations

{% for post in site.publications_foundation reversed %}
  {% include archive-single.html %}
{% endfor %}

## Statistical Privacy

{% for post in site.publications_privacy reversed %}
  {% include archive-single.html %}
{% endfor %}

## Other Data Science Topics

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



