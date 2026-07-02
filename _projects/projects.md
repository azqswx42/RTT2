---
layout: default
title: Projets
---

# Mes projets

Voici une sélection de projets sur lesquels j’ai travaillé.

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }}) 
  {{ project.short }}
{% endfor %}
