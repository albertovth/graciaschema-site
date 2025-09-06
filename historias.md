---
layout: default
title: Historias
permalink: /historias
---

# Historias

Testimonios publicados (curados sin comentarios).

<div class="cards">
  {% for post in site.posts %}
    <article class="card">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <div class="meta">
        {{ post.date | date: "%Y-%m-%d" }}{% if post.author %} · {{ post.author }}{% endif %}
      </div>
      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
      {% endif %}
      <p><a class="button" href="{{ post.url | relative_url }}">Leer historia</a></p>
    </article>
  {% endfor %}
</div>

<p><a class="button" href="#" style="display:inline-block;padding:0.5rem 1rem;background:#eee;border:1px solid #ccc;border-radius:4px;text-decoration:none;color:#000;font-weight:bold;">Botón de prueba</a></p>
