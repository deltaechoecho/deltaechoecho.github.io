---
title: blog
---

  {% for post in site.posts %}
      <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
      <p>{{post.excerpt}}</p>
  {% endfor %}

