---
layout: default
---
<h2>Practicle Chemistry</h2>
<ul>
  {% for post in site.Practicles %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
