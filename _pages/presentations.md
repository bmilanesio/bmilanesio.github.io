---
layout: page
title: Presentaciones
permalink: /presentations/
description: Presentaciones en congresos y eventos.
years: [2021]
nav: true
nav_order: 3
---

<!-- _pages/presentations.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>

