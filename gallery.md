---
title: gallery
image: Pic05.jpg
include_in_nav: true
---

<p>Olympus EM-10, EP-2, and a lot of travel. Prints available on request.</p>

<div class="box alt">
  {% for image in site.static_files %}{% if image.path contains 'images/gallery' %}
  {% if image.path contains 'Pic49' %}<a href="https://500px.com/p/deltaechoecho?view=photos">{% endif %}
  <div class="row uniform 50%"><div class="4u"><span class="image fit"><img src="{{ site.baseurl }}{{ image.path }}" alt="image" /></span></div></div>
  {% if image.path contains 'Pic49' %}</a>{% endif %}
  {% endif %}{% endfor %}
</div>
