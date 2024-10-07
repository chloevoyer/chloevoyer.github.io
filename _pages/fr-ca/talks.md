---
page_id: talks
layout: page
title: présentations
permalink: /talks/
description: "* indique une contribution égale et une co-auteur principal."
nav: true
nav_order: 5
pretty_table: true
---

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">
    
<h1>oral presentations</h1>
{% bibliography --query @presentation %}
</div>

<h2>conferences attended</h2>

<div class="conférences">

<div class="table-responsive table-borderless">
<table class="table-borderless" id="table" data-toggle="table" data-url="{{ 'assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-field="date">Date</th>
      <th data-field="conference">Conférence</th>
      <th data-field="location">Emplacement</th>
    </tr>
  </thead>
</table>
</div>

