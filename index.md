---
layout: home
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
      Welcome to my professional website. I’m a passionate data scientist, consultant, and academic dedicated to addressing complex challenges with innovative data solutions. With consulting experience at industry leaders like Valcon and PwC Denmark and a strong academic background from Copenhagen Business School and Ludwig-Maximilians-University Munich, I blend rigorous theoretical expertise with managing the end-to-end lifecycle of real-world AI/ML applications.
    </p>
    <p>
      Whether it’s developing and implementing custom neural net architectures, designing mathematical models, or leading data-driven consulting projects, my goal is to drive digital and green transformations across sectors.
    </p>
  </div>
</section>

<section class="widget widget-portfolio">
  <div class="container">
    <h2>Project Articles</h2>
    <ul class="post-list">
      {% for project in site.portfolio limit:3 %}
      <li>
        <a href="{{ project.url }}">{{ project.title }}</a>
        <span class="post-date">{{ project.date | date: "%B %d, %Y" }}</span>
      </li>
      {% endfor %}
    </ul>
    <a href="/portfolio/" class="btn btn-secondary">View All Portfolio Projects</a>
  </div>
</section>