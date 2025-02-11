---
layout: home
title: "Blog"
permalink: /blog/
---

Welcome to my blog. Here I publish high-level articles about my projects, insights on data science, AI, and more.

{% if paginator.posts %}
  {% for post in paginator.posts %}
    <article class="post">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </article>
  {% endfor %}

  <nav class="pagination">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path }}" class="prev">Previous</a>
    {% endif %}
    <span class="page-number">Page {{ paginator.page }} of {{ paginator.total_pages }}</span>
    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path }}" class="next">Next</a>
    {% endif %}
  </nav>
{% else %}
  <p>No blog posts available yet. Please check back later.</p>
{% endif %}