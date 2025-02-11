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
  margin: 1rem 0;
}

/* Style the card as a link with no default blue styling */
a.card {
  display: block;
  padding: 1rem;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 4px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none;
  color: inherit;
}
a.card:hover {
  transform: scale(1.02);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}
.card__header h3 {
  margin: 0;
  font-size: 1.25rem;
}
.card__body p {
  margin: 0.5rem 0 0;
  font-size: 0.95rem;
}
</style>

# Portfolio

Below is a selection of my key projects. Click on a project card for more details.

<div class="cards">
  {% for project in site.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</div>