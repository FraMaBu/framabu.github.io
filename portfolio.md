---
layout: single
title: "Portfolio"
permalink: /portfolio/
---

<style>
/* Card container style */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  grid-gap: 1.5rem;
}

/* Individual card style */
.card {
  position: relative;
  padding: 1rem;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 4px;
  transition: box-shadow 0.3s ease;
}
.card:hover {
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}

/* Make sure content is above the overlay */
.card__header,
.card__body {
  position: relative;
  z-index: 2;
}

/* Invisible link overlay that covers the entire card */
.card-link {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  text-decoration: none;
}
</style>

Below is a selection of my key projects. Click on a project card for more details.

<div class="cards">
  {% for project in site.projects %}
    <div class="card">
      <a class="card-link" href="{{ project.url | relative_url }}"></a>
      <div class="card__header">
        <h3>{{ project.title }}</h3>
      </div>
      <div class="card__body">
        <p>{{ project.description }}</p>
      </div>
    </div>
  {% endfor %}
</div>