---
layout: page
title: "Categories"
permalink: /categories/
---

<h1>Categories</h1>

<ul>
  {% for category in site.categories %}
    <li><a href="{{ site.baseurl }}/categories/{{ category | first }}">{{ category | first | capitalize }}</a></li>
  {% endfor %}
</ul>
