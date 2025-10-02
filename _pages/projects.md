---
layout: page
title: projects
permalink: /projects/
description: Research projects and collaborations in urban analytics and computational social science
nav: true
nav_order: 2
display_categories: []  # 改为空数组，不显示分类
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
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
</div>
