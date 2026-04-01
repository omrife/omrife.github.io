---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<h3>Preprints</h3>
<div class="publications">
  {% bibliography -q @*[pubtype=preprint]* %}
</div>

<!-- <h2 class="year">Journal Articles</h2>
<div class="publications">
  {% bibliography -q @*[pubtype=journal]* %}
</div>

<h2 class="year">Conference Papers</h2>
<div class="publications">
  {% bibliography -q @*[pubtype=conference]* %}
</div> -->