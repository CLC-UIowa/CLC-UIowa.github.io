---
layout: page
permalink: /projects/
title: Projects
description: Funded Projects & Grants.
nav: false
nav_order: 1
---

ADD STUFF HERE.

## Popular Repositories 
{% if site.data.repositories.artifacts %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.artifacts %}
	{% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
