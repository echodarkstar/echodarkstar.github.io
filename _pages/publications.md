---
layout: page
permalink: /publications/
title: publications
description: 
years: [2019]
---
<!-- ### Papers -->

### Technical Reports

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f reports -q @*[year={{y}}]* %}
{% endfor %}
