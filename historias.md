---
layout: default
title: Historias
permalink: /historias
---

# Historias

Testimonios publicados (curados sin comentarios, no podés dejar respuestas aquí).


<ul>
{% raw %}{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>— {{ post.date | date: "%Y-%m-%d" }}{% if post.author %} · {{ post.author }}{% endif %}</small>
  </li>
{% endfor %}{% endraw %}
</ul>
