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

<p>See the full publication list on my <a href="https://scholar.google.com/citations?user=Zx6pKsQAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener">Google Scholar</a>.</p>

<p style="font-size: 0.9rem; color: #666; margin-top: -0.5rem; margin-bottom: 1rem;">* indicates equal contribution.</p>

<div class="publications">

<h2>Preprint</h2>
{% bibliography --query @*[preprint=true]* %}

<h2>Conference</h2>
{% bibliography --query @inproceedings* %}

</div>
