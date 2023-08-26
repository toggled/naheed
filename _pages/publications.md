---
layout: page
permalink: /publications/
title: publications
description: My publications/preprints in reversed chronological order. 
years: [2023, 2020, 2019, 2017]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
