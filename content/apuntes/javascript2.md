---
title: "Objetos Complejos en JavaScript 💻"
date: 2024-11-20
draft: false
tags: ["javascript", "programación", "apuntes"]
categories: ["programación"]

image: "/img/default.jpg"
---

# Objetos Complejos en JavaScript 🚀

En JavaScript, los **objetos complejos** son estructuras fundamentales que permiten almacenar y gestionar datos más avanzados. Son esenciales para construir aplicaciones dinámicas y trabajar con datos de manera eficiente.

---

## **¿Qué es un Objeto?**

Un objeto en JavaScript es una colección de pares clave-valor. Estos valores pueden ser de cualquier tipo, incluidos otros objetos, arreglos y funciones.

```javascript

let objetoEjemplo = {
    clave: "valor",
    numero: 42,
    booleano: true,
    arreglo: [1, 2, 3],
    objetoAnidado: {
        propiedad: "valor"
    },
    metodo: function() {
        return "Soy un método del objeto";
    }
};

```

## **Claves y Valores:**
Las claves (o propiedades) son cadenas por defecto. Los valores pueden ser de cualquier tipo de dato.

```javascript
let persona = {
    nombre: "Ana",
    edad: 25
};
console.log(persona.nombre); // "Ana"
```

## **Propiedades y Métodos:**
Los objetos pueden tener funciones como propiedades, conocidas como métodos.

```javascript
let auto = {
    marca: "Toyota",
    arrancar: function() {
        return "El auto está arrancando.";
    }
};
console.log(auto.arrancar()); // "El auto está arrancando."
```

## **Anidación:**
Los objetos pueden contener otros objetos o arreglos como valores. Esta capacidad es útil para representar datos jerárquicos o estructurados.

```javascript
let casa = {
    direccion: "Calle Falsa 123",
    habitaciones: {
        numero: 3,
        tamanio: "grande"
    },
    decoracion: ["minimalista", "moderna"]
};

// Acceso a objetos anidados
console.log(casa.habitaciones.numero); // 3

// Acceso a arreglos dentro de objetos
console.log(casa.decoracion[1]); // "moderna"
```