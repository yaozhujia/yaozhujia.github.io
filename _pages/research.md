---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 2
---

<div class="research d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for entry in site.data.research %}
      {% if entry.type == "list" %}
        {% include cv/list.html %}
      {% elsif entry.type == "map" %}
        {% include cv/map.html %}
      {% elsif entry.type == "nested_list" %}
        {% include cv/nested_list.html %}
      {% elsif entry.type == "time_table" %}
        {% include cv/time_table.html %}
      {% else %}
        {{ entry.contents }}
      {% endif %}
  {% endfor %}
</div>