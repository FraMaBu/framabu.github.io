---
layout: single
title: "Portfolio"
permalink: /portfolio/
---

# Portfolio

Below is a selection of my key projects. Click on a project card for more details.

<div class="cards">
  {% for project in site.projects %}
    <a class="card" href="{{ project.url | relative_url }}">
      <div class="card__header">
        <h3>{{ project.title }}</h3>
      </div>
      <div class="card__body">
        <p>{{ project.description }}</p>
      </div>
    </a>
  {% endfor %}
</div>