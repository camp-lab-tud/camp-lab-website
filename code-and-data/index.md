---
title: Code and Data
nav:
  order: 2
  tooltip: Open-source code and datasets
---

# {% include icon.html icon="fa-solid fa-code" %}Code and Data

Explore our published open-source code and datasets.

## Featured

{% include list.html data="code_data" component="project-excerpt" filter="group == 'featured'" %}

{% include section.html %}

## All

{% include search-box.html %}

{% assign code_data_tags = "" | split: "" %}

{% for code_data in site.code_data %}
  {% assign code_data_tags = code_data_tags | concat: code_data.tags %}
{% endfor %}

{% include tags.html tags=code_data_tags %}

{% include search-info.html %}

{% include section.html %}

{% include list.html data="code_data" component="project-excerpt" %}

