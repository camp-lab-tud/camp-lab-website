---
title: Publications
nav:
  order: 3
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-bookmark" %}Publications

On this page, you can learn more about our latest research outputs. We are committed to enforcing the [Findable, Accessible, Interoperable, and Reusable (FAIR)](https://www.go-fair.org/fair-principles/) whenever possible and reasonable, for instance, by publishing open-source papers and code. We believe this transparency is beneficial for scientific rigor and reproducibility.

{% include section.html %}

## Featured

{% include list.html data="citations" component="citation" style="rich" filter="group == 'featured'" %}

{% include section.html %}

## All

{% include search-box.html %}

{% assign citation_tags = "" | split: "" %}

{% for citation in site.citations %}
  {% assign citation_tags = citation_tags | concat: citation.tags %}
{% endfor %}

{% include tags.html tags=citation_tags %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" filter="date >= '2021-05-01' and ! title.downcase.include?('conference')" %}
