
---
# pages/inorganic.md
---
---
layout: default
title: Inorganic Chemistry
permalink: /inorganic/
---
<h2>Inorganic Chemistry</h2>
<ul>
  {% for post in site.inorganic %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
