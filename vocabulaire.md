---
layout: default
title: "Vocabulaire"
---

<h2>Articles sur la vocabulaire</h2>
<ul>
  {% for post in site.categories.vocabulaire %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
