---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=8W4eh2UAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Foundations

{% for post in site.publications_foundation reversed %}
  {% include archive-single.html %}
{% endfor %}
