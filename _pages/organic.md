
---
# pages/organic.md
---
---
layout: default
title: Organic Chemistry
permalink: /organic/
---
<h2>Organic Chemistry</h2>
<ul>
  {% for post in site.organic %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
