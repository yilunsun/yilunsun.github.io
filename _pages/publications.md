---
layout: page
permalink: /publications/
title: Publications
description: ∗ indicates equal contributions, † indicates co-corresponding author(s)
years: [2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  <br>
  <br>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

