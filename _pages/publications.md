---
layout: page
permalink: /publications/
title: publications
description: This publication list contains high-quality referenced peer-reviewed proceedings and journals. There are more workshop papers which are included in my CV.
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
