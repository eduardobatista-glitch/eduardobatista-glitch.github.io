---
layout: page
title: Projetos
permalink: /projects/
nav: true
nav_order: 4
description: Projetos de pesquisa e desenvolvimento em agricultura digital, pesca e monitoramento ambiental.
display_categories: [pesquisa, trabalho, atividades]
horizontal: false
---

<h3>Projetos e atividades</h3>

<p>
  Esta seção reúne os principais trabalhos acadêmicos, de pesquisa e extensão desenvolvidos ao longo da trajetória profissional e universitária.
</p>

<div class="row">
  {% assign projects = site.projects | sort: 'importance' %}
  {% for project in projects %}
    <div class="col-md-6 mb-4">
      <div class="card h-100">
        <div class="card-body">
          {% if project.img %}
            <img src="{{ project.img | relative_url }}" alt="{{ project.title }}" class="img-fluid rounded mb-3">
          {% endif %}
          <h4 class="card-title">{{ project.title }}</h4>
          <p class="card-text">{{ project.description }}</p>
          <a href="{{ project.url | relative_url }}" class="btn btn-sm btn-outline-primary">Saiba mais</a>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
