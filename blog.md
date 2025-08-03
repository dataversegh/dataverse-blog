---
layout: default
title: Blog
permalink: /blog/
---
# 📚 Our Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br />
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>