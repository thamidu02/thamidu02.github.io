---
layout: page
title: Blog
permalink: /blog/
---

# 📝 Blog Posts

Below are all my posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}