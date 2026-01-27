---
layout: default
title: Tags
---

# Tags

{% for tag in site.tags %}
## {{ tag[0] }}

<ul>
  {% for post in tag[1] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      ({{ post.date | date: "%Y-%m-%d" }})
    </li>
  {% endfor %}
</ul>
{% endfor %}
