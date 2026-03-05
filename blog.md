---
layout: default
title: Blog
permalink: /blog/
---
# Blog

Anything from Structural Biology to Data Science

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%b %-d, %Y" }}</li>
{% endfor %}
</ul>
