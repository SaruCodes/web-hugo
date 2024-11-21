---
title: "Shortcodes en Hugo"
date: 2024-11-21
layout: "single"
tags: ["markdown","hugo", "util"]
description: "Aprende cómo usar shortcodes en Hugo."
draft: false
image: "/img/default.jpg"
---

# Shortcodes en Hugo

Los **shortcodes** en Hugo son herramientas potentes que permiten insertar contenido enriquecido como imágenes, videos, y otros elementos de manera sencilla en tus archivos Markdown. Estos son algunos de los shortcodes más útiles y cómo emplearlos.

---

## 1. Imágenes

Para insertar imágenes usando el shortcode `figure`, puedes agregar una descripción opcional y un pie de foto.

```markdown
{{< figure src="/ruta/a/la/imagen.jpg" title="Pie de foto opcional" alt="Texto alternativo" >}}
