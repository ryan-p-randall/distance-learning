---
permalink: /cv/
title: "CV"
layout: single
author_profile: true
---

{% include toc title="Table of Contents" %}

## Education

* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2023 (expected)

## Work Experience

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
## Skills

* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

## Publications

<!-- hiding this section with an html comment; delete the lesser than, exclamation point, hyphens, and closing greater than sign if you want a "publications" section above all the other sections

### Publications  
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

-->

### Books  
  <ul>{% for post in site.books %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{:.no_toc}

### Articles  
  <ul>{% for post in site.articles %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{:.no_toc}

<!--   
  <ul>{% for post in site.articles %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}</ul>
-->

### Thesis  
  <ul>{% for post in site.theses %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{:.no_toc}
  
## Talks

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>{:.no_toc}
  
## Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{:.no_toc}
  
## Service and Leadership

  <ul>{% for post in site.service %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>{:.no_toc}

