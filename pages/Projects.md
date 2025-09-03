---
layout: single
title: "Projects"
permalink: /projects/
---

<div class="grid__wrapper">
  {% for project in site.projects %}
    <div class="grid__item">
      <a href="{{ project.url }}">
        <img src="{{ project.image }}" alt="{{ project.title }}">
        <p>{{ project.title }}</p>
      </a>
    </div>
  {% endfor %}
</div>
