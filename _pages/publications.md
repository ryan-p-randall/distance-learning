---
title: "Publications"
permalink: /publications/
layout: single
author_profile: true
---

:construction: :construction: :construction:  
This page under construction.  
:construction: :construction: :construction:  
{: .notice}

To make the CV categories work, each different type of publication has to live in a different folder. I'm trying to make a single "publications" page that will combine all the different types (articles, books, papers, whatever) into a single view. I'm not sure that's possible. Until I get it working or determine that it's truly not possible, you might want to change the text of the above notice.  
{: .notice--info}

<ul>
  {% for post in site.posts %}
    {% for post in site.tag.publication %}
    <li>{% include archive-single-talk-cv.html %}</li>
    {% endfor %}
  {% endfor %}
</ul>