---
layout: default
title: Compartí tu recuerdo
permalink: /comparti
---

<p>
  <a class="cta" href="{{ '/' | relative_url }}">Volver al inicio</a>
</p>

# Compartí tu recuerdo

Gracias por contribuir a este homenaje. Tu aporte va a ser **revisado** antes de publicarse para mantener un espacio respetuoso y fiel a su legado.

<p style="color:#001f3f;font-weight:600">
Después de enviar, la página mostrará la confirmación arriba del formulario.
Si la pantalla parece quedar en blanco, no te preocupés: el sitio te llevará hacia arriba automáticamente.
</p>

<div style="max-width:820px;margin:0 auto">
  <iframe
    id="formFrame"
    src="https://docs.google.com/forms/d/e/1FAIpQLSdz3hoilu42x17f_vFs2EDMFL--LvcAlMyTF1HeA3onkDu3VA/viewform?embedded=true"
    width="100%" height="900" frameborder="0" marginheight="0" marginwidth="0">
    Cargando…
  </iframe>
</div>

<script>
  (function () {
    var f = document.getElementById('formFrame');
    if (!f) return;
    f.addEventListener('load', function () {
      f.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  })();
</script>

<p>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLSdz3hoilu42x17f_vFs2EDMFL--LvcAlMyTF1HeA3onkDu3VA/viewform"
     target="_blank" rel="noopener" class="cta">
    Abrir el formulario en otra pestaña
  </a>
</p>
