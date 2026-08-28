---
layout: archive
title: "Other Interests"
permalink: /other/
author_profile: true
---

Personal interests, photography, and creative hobbies outside of academia.

{% for post in site.other reversed %}
  {% include archive-single.html %}
{% endfor %}
