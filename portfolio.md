---
title: gallery
image: Pic05.jpg
include_in_nav: true
---

Olympus EM-10, EP-2, and a lot of travel. Prints available on request.

<div class="box alt">
  {% for image in site.static_files %}
  {% if image.path contains 'images/gallery/Pic' %}
  <div class="row uniform 50%"><div class="4u">
    <span class="image fit">
      <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    </span>
  </div>
  </div>
  {% endif %}
  {% endfor %}
</div>
