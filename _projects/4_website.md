---
layout: page
title: Open-source Pickup Soccer Group websites
description: Create website for community pickup soccer groups
img:
importance: 3
category: incubator
---

We will help to grow community pickup soccer groups by creating an github repo in the OpenFutbol Github Organization.
Each Accepted Community Pickup Soccer group will get a website stood up for them for free.  
Join the discord and let us know you are interested.  

## GitHub users

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

---

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

