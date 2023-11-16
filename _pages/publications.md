---
layout: page
permalink: /publications/
title: Publications
description: This page collects a(n incomplete) list of Jie Zhao's publications. Posters and workshp papers without formal proceedings are not recorded. More information is available at <a href='https://scholar.google.com/citations?hl=en&user=9EIFPO4AAAAJ'>Google Scholar</a> and <a href='https://dblp.org/pid/23/3168-2'>dblp</a>. The pdf copies are the author versions, posted by permission of ACM or other publishers for personal use but not for redistribution.
years: [2023, 2022, 2021, 2020, 2019, 2018]
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
