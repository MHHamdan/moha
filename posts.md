---
layout: posts
title: "Blog Posts"
permalink: /posts/
---

<h1>Blog Posts</h1>

{% for post in site.posts %}
  <div>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><small><i>{{ post.date | date_to_string }}</i></small></p>
    <p>{{ post.excerpt }}</p>
  </div>
  <hr>
{% endfor %}
