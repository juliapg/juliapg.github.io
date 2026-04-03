---
layout: page
title: Research
permalink: /projects/
description: 
nav: false
nav_order: 3
horizontal: true
---

{% assign sorted_projects = site.projects | sort: "importance" %}

<div class="projects">
  <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>