---
layout: page
title: Procès-verbaux
permalink: /proces-verbaux/
---

<div class="list-group posts-list">
  {% for document in site.proces-verbaux %}
  <a class="list-group-item" href="{{ document.url | relative_url }}">
    {{ document.title | escape }}
  </a>
  {% endfor %}
</div>
