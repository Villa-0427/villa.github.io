---
title: "Diagrama Entidad-Relación (Modelo de Peter Chen)"
pubDate: 2026-08-12
description: "Un modelo Entidad-Relación estilo Peter Chen, realizado como parte de mis estudios universitarios, sobre un sistema de gestión de equipos, jugadores, árbitros y partidos."
tags: [bases-de-datos, sql, universidad, modelado]
category: general
draft: false
pin: false
image:
  path: "/images/blog/Diagrama%20MER.png"
  alt: "Diagrama Entidad-Relación estilo Peter Chen de un sistema de equipos, jugadores, árbitros y partidos"
---

Como parte de mis estudios universitarios, elaboré este Modelo de Entidad-Relación siguiendo la notación de **Peter Chen**, una de las formas clásicas de representar bases de datos antes de pasar al modelo relacional.

## Sobre el diagrama

El modelo representa un sistema para gestionar equipos, jugadores, árbitros y partidos, e incluye:

- Entidades como **Equipo**, **Jugador**, **Árbitro**, **Partido** y **Tabla** (de posiciones).
- Relaciones como **Pertenecer**, **Dirigir**, **Jugar** y **Pitar**, cada una con sus respectivas cardinalidades (1, M, N).
- Atributos compuestos, como el **Nombre**, que se descompone en primer nombre, segundo nombre, primer apellido y segundo apellido.
- Atributos identificadores (subrayados), como la **Cédula** del jugador y la **Posición** en la tabla.

Este tipo de ejercicios me ayuda a fortalecer mi base en el diseño de bases de datos, algo que complementa directamente lo que vengo trabajando con SQL.

href="https://drive.google.com/file/d/1cahBydYzQ3oKHvhdKzybdEcxcO7j3Joy/view?usp=sharing"
  
Ver el proyecto completo ↑
</a>

