---
layout: single
title: "Portfolio"
permalink: /portfolio/
---

# Portfolio

Below is a selection of my key projects. Click on a project card for more details.

<div class="cards">
  {% for project in site.projects %}
    <div class="card">
      <div class="card__header">
        <h3>{{ project.title }}</h3>
      </div>
      <div class="card__body">
        <p>{{ project.description }}</p>
      </div>
      <div class="card__footer">
        {% if project.github %}
          <a href="{{ project.github }}" class="btn btn--small" target="_blank">GitHub</a>
        {% endif %}
        {% if project.blog %}
          <a href="{{ project.blog }}" class="btn btn--small">Blog Article</a>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>