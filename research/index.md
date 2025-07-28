---
title: Research
nav:
  order: 1
  tooltip: Ongoing and past research topics
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research projects

Learn more about our research.

## Featured

{% include list.html data="projects" component="project-excerpt" filter="group == 'featured'" %}

{% include section.html %}

## All present and past projects

{% include search-box.html %}

{% assign project_tags = "" | split: "" %}

{% for project in site.projects %}
  {% assign project_tags = project_tags | concat: project.tags %}
{% endfor %}

{% include tags.html tags=project_tags %}

{% include search-info.html %}

{% include section.html %}

<div class="project-excerpt-container">
  {% include project-list.html data="projects" component="project-excerpt" %}
</div>

