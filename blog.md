---
title: blog
---
{% for post in site.posts %}
      <a href="{{ post.url }}">
      <h3 class="major">{{ post.title }}</h3>
      </a>
      <p>{{post.excerpt}}</p>
{% endfor %}

