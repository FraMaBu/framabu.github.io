---
layout: single
title: "Welcome"
permalink: /
author_profile: true
header:
  overlay_image: "/assets/images/banner.jpg"
  caption: "Solving Problems with Data"
  cta:
    - label: "Portfolio"
      url: /portfolio/
    - label: "CV"
      url: /cv/
---

<section class="intro">
  <div class="container">
    <h1 class="page-title">Hi, I'm Franz Buchmann, PhD 👋</h1>
    <p class="lead">Senior Data Scientist | Consultant | Researcher</p>
    <p>
      Welcome to my professional website. I’m a passionate data scientist, consultant, and academic dedicated to addressing complex challenges with innovative data solutions.
    </p>
    <p>
      With consulting experience at industry leaders like Valcon and PwC Denmark and a strong academic background from Copenhagen Business School and Ludwig-Maximilians-University Munich, I blend rigorous theoretical expertise with managing the end-to-end lifecycle of real-world AI/ML applications.
    </p>
    <p>
      Whether it’s developing and implementing custom neural net architectures, designing mathematical models, or leading data-driven consulting projects, my goal is to drive digital and green transformations across sectors.
    </p>
  </div>
</section>

<section class="widget widget-portfolio">
<div class="portfolio-carousel">
  {% include recent_posts.html collection="portfolio" limit=5 %}
</div>
</section>