---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">
{% bibliography %}
</div>

<style>
.publications img {
    transition: transform 0.3s ease;
}
.publications img:hover {
    transform: scale(1.05);
}
</style>
