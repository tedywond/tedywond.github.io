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

## Manual Publications List

<div class="row">
    <div class="col-sm-2">
        <img src="/assets/img/publication_preview/progressor.png" class="img-fluid z-depth-1" alt="PROGRESSOR" />
    </div>
    <div class="col-sm-10">
        <h5>PROGRESSOR: Progressive Learning for Robust Robot Skill Acquisition</h5>
        <p>
            <strong>Links:</strong>
            <a href="https://arxiv.org/pdf/2411.17764" target="_blank">arXiv</a> |
            <a href="https://ripl.github.io/progressor/" target="_blank">Project Page</a>
        </p>
    </div>
</div>

<div class="row mt-4">
    <div class="col-sm-2">
        <img src="/assets/img/publication_preview/domain_adaptation.png" class="img-fluid z-depth-1" alt="Domain Adaptation" />
    </div>
    <div class="col-sm-10">
        <h5>Unsupervised Domain Adaptation for Plant Organ Counting</h5>
        <p>
            <strong>Links:</strong>
            <a href="https://github.com/p2irc/UDA4POC" target="_blank">GitHub</a>
        </p>
    </div>
</div>

<style>
.publications img {
    transition: transform 0.3s ease;
}
.publications img:hover {
    transform: scale(1.05);
}
</style>
