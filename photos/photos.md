---
layout: default
title: Photos
permalink: photos/
---

Art and science are deeply interconnected - two expressions of the same desire to explore and shape the way we see and understand the world. Photography allows me to express how I see our interaction with technology evolving, reflecting on its power to both transcend nature's limitations and exert control over our lives.

<div class="photo-grid">
{% for i in (1..20) %}
  <div class="photo-item">
    <img src="{{ site.baseurl }}/Photography/{{ i }}.jpg" alt="Photo {{ i }}">
  </div>
{% endfor %}
</div>

