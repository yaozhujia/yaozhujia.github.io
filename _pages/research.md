---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 2
---

{% for entry in site.data.research %}
<div class="card mt-3 p-3">
  <h3 class="card-title font-weight-medium">{{ entry.title }}</h3>
  <div>
      {{ entry.contents }}
  </div>
</div>
{% endfor %}