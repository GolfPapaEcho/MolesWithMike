
---
# pages/practical.md
---
---
layout: default
title: Practical Chemistry
permalink: /practical/
---
<h2>Practical Chemistry</h2>
<ul>
  {% for post in site.practical %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
