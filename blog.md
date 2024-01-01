---
layout: default
title: Blog
---

# This is where I post cool things I build that don't make it to LinkedIn

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
