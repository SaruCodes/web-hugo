---
title: "Markdown básico"
date: 2024-11-15
layout: "single"
tags: ["markdown","util"]
description: "Una guía básica sobre la sintaxis de Markdown"
draft: false
image: "/img/default.jpg"
---

# Guía de Sintaxis Markdown

Este artículo ofrece un ejemplo básico de la sintaxis de Markdown que puedes usar en archivos de contenido Hugo, además de mostrar cómo se aplican los elementos HTML básicos decorados con CSS en un tema Hugo.

---

## 1. Encabezados

Los siguientes elementos HTML `<h1>—<h6>` representan seis niveles de encabezados de sección. `<h1>` es el nivel más alto, mientras que `<h6>` es el más bajo.

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6

```

---

## 2. Estilos de Texto

Markdown permite aplicar diferentes estilos al texto:

- *Negrita:* Se utiliza doble asterisco `**` o doble guion bajo `__` alrededor del texto.
- *Cursiva:* Se utiliza un asterisco `*` o un guion bajo `_` alrededor del texto.
- *Negrita y cursiva:* Combina tres asteriscos `***` alrededor del texto.
- *Tachado:* Se utiliza doble tilde `~~` alrededor del texto.

```markdown
**Este texto está en negrita**
*Este texto está en cursiva*
***Este texto tiene ambos estilos***
~~Este texto está tachado~~
```

**Este texto está en negrita**
*Este texto está en cursiva*
***Este texto tiene ambos estilos***
~~Este texto está tachado~~

---

## 3. Listas

### 3.1 Listas Desordenadas
Se crean utilizando un guion `-`, un asterisco `*`, o un signo `+` seguido de un espacio. Puedes anidar elementos con sangría.

```markdown
- Elemento 1
- Elemento 2
    - Sub-elemento 2.1
```
- Elemento 1
- Elemento 2
    - Sub-elemento 2.1

---

### 3.2 Listas Ordenadas
Se crean con números seguidos de un punto y un espacio. El número no necesita ser secuencial, Markdown se encarga de formatearlo correctamente.

```markdown
1. Primer elemento
2. Segundo elemento
```

1. Primer elemento
2. Segundo elemento

---

## 4. Citas

Las citas se crean usando el símbolo `>` seguido de un espacio. Puedes usarlas para destacar textos, como frases célebres o ideas importantes.

```markdown
> "El conocimiento es poder." - Francis Bacon
```
> "El conocimiento es poder." - Francis Bacon
