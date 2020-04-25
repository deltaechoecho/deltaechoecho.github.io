---
title: blog
image: Pic40.jpg
include_in_nav: true
---
<div>
{% for post in site.posts %}
      <div>
      <!-- <a href="{{ post.url }}"> -->
            <h6>{{ post.date | date: '%B %d, %Y' }}</h6>
            <h3>{{ post.title }} </h3>
      <!-- </a> -->
      {{post.content}}
      <br />
      </div>
{% endfor %}
</div>
