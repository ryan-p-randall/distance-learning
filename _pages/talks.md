---
title: "Talks"
permalink: /talks/
layout: single
author_profile: true
toc: false
---

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}