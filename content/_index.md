+++
title = "inicio"
+++

# Bienvenido a mi blog

Soy desarrollador apasionado por la tecnología, el código abierto y el aprendizaje continuo. Aquí comparto mis experiencias, tutoriales y reflexiones sobre el mundo del desarrollo.

Soy un estudiante de economía intentando aprender todas las herramientas necesarias para destacar, usando tecnología que me permita mantenerme a la vanguardia de los avances el ámbito técnico.

## Últimos posts

{% set blog = get_section(path="blog/_index.md") %}
{% for page in blog.pages | slice(end=3) %}
- **[{{ page.title }}]({{ page.permalink }})** - {{ page.date | date(format="%d/%m/%Y") }}
{% endfor %}

[Ver todos los posts →](/blog/)

## Sobre este sitio

Este blog está construido con:
- **[Zola](https://www.getzola.org/)** - Generador de sitios estáticos ultra-rápido
- **[tabi](https://github.com/welpo/tabi)** - Tema moderno y accesible
- **[Cloudflare Pages](https://pages.cloudflare.com/)** - Hosting y CDN global gratuito

¡Espero no aburrir!
