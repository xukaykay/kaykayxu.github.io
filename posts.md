---
layout: default
title: Posts
---

# All My Posts Are Here

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date }}</p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
