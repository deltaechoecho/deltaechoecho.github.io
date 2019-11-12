---
title: blog
---
<div>
{% for post in site.posts %}
      <div>
      <!-- <a href="{{ post.url }}"> -->
      <h3>{{ post.title }} :: {{ post.date | date: '%B %d, %Y' }}</h3>
      <!-- </a> -->
      <p>{{post.excerpt}}</p>
      </div>
{% endfor %}
</div>
