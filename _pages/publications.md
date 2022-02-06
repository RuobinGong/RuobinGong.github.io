---
layout: archive
title: ""
permalink: /publications/
author_profile: true

---

{% include base_path %}

# On inference foundations:

{% for post in site.publications_foundation reversed %}
  {% include archive-single.html %}
{% endfor %}

# On statistical privacy:

{% for post in site.publications_privacy reversed %}
  {% include archive-single.html %}
{% endfor %}

# On other data science topics:

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



