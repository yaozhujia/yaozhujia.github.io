---
layout: page
permalink: /publications/
title: Publications
description: This page collects an incomplete set of the publications of Dr. Jie Zhao. Posters and workshp papers without formal proceedings are not recorded. More information is available at <a href='https://scholar.google.com/citations?hl=en&user=9EIFPO4AAAAJ'>Google Scholar</a> and <a href='https://dblp.org/pid/23/3168-2'>dblp</a>.
years: [2022, 2021, 2020, 2019, 2018, 2017]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
