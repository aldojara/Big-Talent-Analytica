---
layout: default
title: "Catálogo de Cursos"
permalink: /cursos/
---
# Catálogo de Cursos
{% for c in site.data.courses %}
  {% include course-card.html course=c %}
{% endfor %}
