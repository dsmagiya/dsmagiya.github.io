---
layout: page
permalink: /publications/
title: publications
description: Papers, preprints, and Microscopy & Microanalysis abstracts with DOIs, newest first.
nav: true
nav_order: 2
---

[Google Scholar](https://scholar.google.com/citations?user=rs92hE4AAAAJ&hl=en)

{% include bib_search.liquid %}

## Work in Progress

<div class="publications">

{% bibliography --query @*[keywords=preprint] --group_by none %}

</div>

## Publications

<div class="publications">

{% bibliography --query @*[keywords=published] --group_by none %}

</div>
