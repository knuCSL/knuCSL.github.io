---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
title: Publications
---

<!-- _pages/publications.md -->

<div style="margin-bottom:1.5rem;">
  <a href="{{ '/publications-ko/' | relative_url }}" style="font-size:0.85rem; color:var(--global-theme-color); text-decoration:none; border:1px solid var(--global-theme-color); padding:0.25rem 0.6rem; border-radius:4px;">한국어</a>
</div>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
