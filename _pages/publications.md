---
layout: page
permalink: /publications/
title: publications
description: "* denotes equal contribution and joint lead authorship."
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
    
<h1>peer-reviewed articles</h1>
{% bibliography --query @article %}

<h2>conference proceedings</h2>
{% bibliography --query @inproceedings %}

<h1>preprints</h1>
{% bibliography --query @preprint %}

<h1>in preparation</h1>
{% bibliography --query @unpublished %}

<h1>presentations</h1>
{% bibliography --query @presentation %}

</div>
