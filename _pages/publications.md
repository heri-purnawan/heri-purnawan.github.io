---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

Please check the up-to-date list on <a href='https://scholar.google.com/citations?user=5uDKOUMAAAAJ&hl=en&oi=ao' style="color:#36AE7C;" >Google Scholar</a>.
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
