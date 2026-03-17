---
layout: page
permalink: /repositories/
title: repositories
description: A selection of my GitHub repositories.
nav: true
nav_order: 3
---

{% if site.data.repositories.github_users %}

## GitHub stats

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
