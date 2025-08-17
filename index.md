---
layout: home
title: "Inicio"
permalink: /
---

## Proyectos destacados

<section class="projects-grid">
  {% for i in (1..3) %}
  <div class="project-card">
    <img src="/assets/img/proyecto{{ i }}.png" alt="Proyecto {{ i }}">
    <h3>Proyecto {{ i }}</h3>
    <p>Descripción breve del proyecto {{ i }}.</p>
    <a href="/portfolio/#proyecto{{ i }}">Ver más</a>
  </div>
  {% endfor %}
</section>
