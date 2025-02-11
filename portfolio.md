---
layout: single
title: "Portfolio"
permalink: /portfolio/
---

{% include card-styles.html %}

Below is a selection of my key projects. Click on a project card for more details.

<div class="cards">
  {% for project in site.projects %}
    {% include card-contents.html project=project %}
  {% endfor %}
</div>