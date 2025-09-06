# Gracias, Chema — Jekyll (GitHub Pages) Skeleton

Sitio mínimo con **tres páginas** y un **blog de historias**:

- `index.md` — Inicio
- `comparte.md` — Formulario (incrusta tu Google Form)
- `historias.md` — Lista de historias (muestra `site.posts`)
- `_posts/YYYY-MM-DD-titulo.md` — Cada historia como entrada Markdown

## Pasos rápidos (web UI, sin terminal)

1. Crea un repositorio en GitHub llamado `graciaschema-site` (público).
2. Sube **todos estos archivos** a la raíz del repo (drag & drop).
3. En el repo: **Settings → Pages → Source: Deploy from a branch** → `main` / `/ (root)` → **Save**.
4. Espera 1–2 minutos. Tu sitio queda en: `https://TUUSUARIO.github.io/graciaschema-site/`.

## Google Form

- Crea tu formulario → **Enviar → <> (Incrustar)** → copia el `<iframe>`.
- Edita `comparte.md` y **reemplaza** el iframe de ejemplo.
- Commit, espera 1–2 minutos y listo.

## Publicar nuevas historias

1. En GitHub → **Add file → Create new file**.
2. Nombre del archivo: `_posts/AAAA-MM-DD-titulo-con-guiones.md`
3. Pega esta plantilla y edítala:

```markdown
---
layout: post
title: "TÍTULO DE LA HISTORIA"
author: "Nombre o Anónimo"
date: AAAA-MM-DD
---

Texto de la historia en Markdown.
```

4. **Commit**. Aparece automáticamente en `/historias`.

## Dominio personalizado (opcional)

- Crea un archivo `CNAME` en la raíz con tu dominio (p. ej. `graciaschema.org`).
- En tu proveedor de dominio, apunta `www` como CNAME a `TUUSUARIO.github.io`.
- Activa HTTPS en **Settings → Pages** cuando esté disponible.

## Notas

- Tema: `jekyll-theme-cayman` (nativo de GitHub Pages, limpio).
- Sin comentarios públicos; el control editorial es tuyo (curas lo que publicas).
- Puedes cambiar el look más tarde cambiando `theme:` en `_config.yml`.

---

**Guía rápida para tu coeditor (periodista):**  
1) Ir al repo → `Add file → Create new file`  
2) Nombrar `_posts/AAAA-MM-DD-titulo.md`  
3) Pegar la plantilla de historia (arriba)  
4) `Commit` y listo.
