---
layout: default
title: Jacob McNamara - Portfolio
permalink: /projects/
---
<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project._pages/Statics | relative_url }}" alt="{{ project.Statics }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>