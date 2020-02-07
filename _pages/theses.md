---
title: "Theses"
permalink: /theses/
layout: single
author_profile: true
toc: false
---

{% for post in site.theses reversed %}
  {% include archive-single-talk.html %}
{% endfor %}