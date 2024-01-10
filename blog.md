---
layout: default
title: Blog
---

# This is where I post cool things that don't make it to LinkedIn

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
