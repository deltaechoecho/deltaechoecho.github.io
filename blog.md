---
title: blog
---
<div>
{% for post in site.posts %}
      <div>
      <a href="{{ post.url }}">
      <h3 class="major">{{ post.title }}</h3>
      </a>
      <p>{{post.excerpt}}</p>
      </div>
{% endfor %}
</div>
