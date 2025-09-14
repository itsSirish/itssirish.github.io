---
layout: page
title: Categories
permalink: /categories/
---
<p>This page lists all categories on the site.</p>

<ul>
{% for category in site.categories %}
  {% assign name = category[0] %}
  <li><a href="{{ site.baseurl }}/categories/{{ name | slugify }}/">{{ name }} ({{ category[1].size }})</a></li>
{% endfor %}
</ul>
