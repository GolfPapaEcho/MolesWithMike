---
# pages/physical.md
---
---
layout: default
title: Physical Chemistry
permalink: /physical/
---
<h2>Physical Chemistry</h2>
<ul>
  {% for post in site.physical %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
