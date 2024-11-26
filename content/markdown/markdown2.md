---
title: "Markdown avanzado"
date: 2024-11-15
layout: "single"
tags: ["markdown","util"]
description: "Una guía de markdown más avanazada incluyendo shortcode"
draft: false
image: "./img/default.jpg"
---
# Guía Avanzada de Markdown y Shortcodes en Hugo

Markdown es un lenguaje de marcado ligero que facilita la creación de contenido. En esta guía, exploraremos características avanzadas y cómo Hugo permite extender su funcionalidad con **shortcodes**.

---

## Características Avanzadas de Markdown

### 1. Tablas
Puedes crear tablas para organizar datos de forma sencilla:

```markdown
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Dato 1    | Dato 2    | Dato 3    |
| Dato A    | Dato B    | Dato C    |
```

| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Dato 1    | Dato 2    | Dato 3    |
| Dato A    | Dato B    | Dato C    |

---

## Shortcode

## 1. Uso de Shortcodes Predeterminados 
Hugo incluye varios shortcodes predefinidos. Por ejemplo:

### Insertar un video de YouTube

```markdown
{{< youtube a7_WFUlFS94 >}}


---

### Mostrar código en línea

```markdown
{{< highlight python >}}
def saludo(nombre):
return f"Hola, {nombre}!"
{{< /highlight >}}
```

## 2. Crear tus propios Shortcodes
Puedes definir shortcodes personalizados en el directorio layouts/shortcodes/.