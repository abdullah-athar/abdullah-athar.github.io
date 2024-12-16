---
layout: category
title: "Blogs"
permalink: /blogs/
category: blogs
---

<div class="post-grid">
  {% for post in site.posts %}
  {% if post.categories contains "blogs" %}
  <div class="post-card">
    <a href="{{ post.url }}">
      <div class="post-thumbnail" style="background-image: url('{{ post.featured_image | default: '/assets/images/default-thumbnail.jpg' }}');"></div>
      <div class="post-info">
        <h2>{{ post.title }}</h2>
        <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
      </div>
    </a>
  </div>
  {% endif %}
  {% endfor %}
</div>
