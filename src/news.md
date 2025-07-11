---
title: Blog
layout: layouts/base.njk
---

# Blog Posts

<ul>
  {% for post in collections.news %}
    <li>
      <a href="{{ post.url }}">{{ post.data.title }}</a> —
      <small>{{ post.date  }}</small>
    </li>
  {% endfor %}
</ul>
