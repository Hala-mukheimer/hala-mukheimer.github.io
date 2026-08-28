---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

A selection of technical projects and academic research implementations.

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
