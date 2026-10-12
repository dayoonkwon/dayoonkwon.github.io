---
layout: page
title: research
permalink: /research/
description: From environmental exposure, to molecular embedding, to disease.
nav: true
nav_order: 1
horizontal: false
---

My research follows one path. Environmental exposures such as air pollution leave molecular traces in the epigenome, metabolome, and microbiome. I measure those traces, build biomarkers and aging clocks from them, and test how they lead to chronic disease, with a particular focus on the brain.

<!-- pages/projects.md -->
<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
