---
layout: default
title: Your Site Name
---

# Welcome to My Creative Space

*An artistic journey through code and design.*

## Featured Projects

Here, you can list your most notable projects or link to them.

- [Project Name 1](link-to-project)
- [Project Name 2](link-to-project)
- [Project Name 3](link-to-project)

## Latest Blog Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

## About Me

A brief section about you. Maybe include your philosophy, inspirations, or goals.

## Connect with Me

Links to your social media or professional networks.

- [GitHub](your-github-link)
- [LinkedIn](your-linkedin-link)
- [Twitter](your-twitter-link)

<footer>
  © {{ site.time | date: '%Y' }} - All Rights Reserved.
</footer>
