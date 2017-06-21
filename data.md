---
layout: page
title: Data
permalink: /data/
---

<ul>
{% for monument in site.data.mlab2 %}
  <li>
{% endfor %}
</ul>

<ul>
{% for novels in site.data.end-19c-epi %}
  <li>
    <strong>{{ novels.title }}</strong>
  </li>
{% endfor %}
</ul>
