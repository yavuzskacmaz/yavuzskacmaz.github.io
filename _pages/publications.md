---
layout: page
permalink: /Research/
title: Research
description: #
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @article %}

<h2 class="bibliography">Working Papers</h2>

{% bibliography --query @techreport --group_by none %}

</div>
