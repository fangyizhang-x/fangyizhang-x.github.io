---
layout: page
title: ERA Lab
permalink: /projects/
description: Research in the ERA Lab (including projects conducted  the director Fangyi Zhang during his past experience.
nav: true
nav_order: 3
display_categories: [Robotics and AI, AI, Beyond]
horizontal: false
---

# ERA Lab – Embodied Robotics & AI Lab

The **Embodied Robotics & AI Lab (ERA Lab)**, led by [Dr. Fangyi Zhang](https://staffportal.curtin.edu.au/staff/profile/view/fangyi-zhang-a9c650e7/), focuses on advancing robotics and AI to equip robots with real-world skills. Since 2014, Dr. Zhang has specialized in robotics and AI, contributing extensively to research and innovation in the field.

We welcome collaborations with industry partners and researchers, as well as students interested in robotics and embodied AI. For inquiries, please contact [Dr. Fangyi Zhang](mailto:fangyi.zhang@curtin.edu.au).

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
