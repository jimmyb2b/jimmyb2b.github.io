---
layout: default
title: 首页
---

# 文章列表

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date_to_string }})
    </li>
  {% endfor %}
</ul>
