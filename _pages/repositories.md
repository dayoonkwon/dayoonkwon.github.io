---
layout: page
permalink: /repositories/
title: repositories
description:
nav: true
nav_order: 3
---

<style>
h1.post-title { display: none; }
</style>

{% if site.data.repositories.github_repos %}

## selected repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
