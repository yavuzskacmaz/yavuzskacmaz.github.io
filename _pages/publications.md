---
layout: page
permalink: /Research/
title: Research
description: #
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<div class="publications">

{% bibliography --query @article %}

<h2 class="bibliography">Working Papers</h2>

{% bibliography --query @techreport --group_by none %}

<h2 class="bibliography">Work in Progress</h2>

{% bibliography --query @unpublished --group_by none %}

</div>
