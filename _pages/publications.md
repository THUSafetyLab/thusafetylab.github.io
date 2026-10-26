
---
layout: page
permalink: /publications/
title: Publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- Publications page: year headings and dividers -->

<style>
/* Make publication years black and more prominent */
.publications h2.bibliography,
.publications h2.year,
.publications h2 {
  color: #000000 !important;
  font-weight: 700 !important;
}

/* Make the horizontal dividers black */
.publications h2.bibliography,
.publications h2.year {
  border-bottom-color: #000000 !important;
  border-top-color: #000000 !important;
}

/* al-folio year grouping divider */
.publications .year {
  color: #000000 !important;
  border-color: #000000 !important;
}

/* Dividers implemented with pseudo-elements */
.publications h2.bibliography::before,
.publications h2.bibliography::after,
.publications h2.year::before,
.publications h2.year::after {
  border-color: #000000 !important;
  background-color: #000000 !important;
}
</style>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">
  {% bibliography %}
</div>
