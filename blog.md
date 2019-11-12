---
title: blog
---
<div>
{% for post in site.posts %}
      <div>
      <!-- <a href="{{ post.url }}"> -->
            <h3>{{ post.title }} </h3>
            <h6>{{ post.date | date: '%B %d, %Y' }}</h6>
      <!-- </a> -->
      {{post.excerpt}}
      </div>
{% endfor %}
</div>
