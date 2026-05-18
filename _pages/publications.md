---
layout: page
permalink: /publications/
title: Research
description: <h6>Recent publications and preprints. For a complete list with latest updates, check out <b><a href='https://scholar.google.com/citations?user=419WltwAAAAJ'>Google Scholar</a></b>.</h6>
years: [2026, 2025, 2024, 2023, 2022, 2021,2020,2019, 2018, 2017, 2016, 2015, 2014, Thesis]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
