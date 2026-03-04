# Factory Method - Ejemplo de UI Multiplataforma

[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.java.com)
[![Patrón: Factory Method](https://img.shields.io/badge/Patrón-Factory%20Method-green.svg)](https://refactoring.guru/design-patterns/factory-method)

## Descripción

Este ejercicio implementa el patrón de diseño **Factory Method** aplicado a elementos de interfaz de usuario. El ejemplo muestra cómo crear botones que tienen la misma funcionalidad pero diferente comportamiento según la plataforma (Windows/HTML), sin acoplar el código cliente a clases concretas.

## El problema que resuelve

Una aplicación necesita ejecutarse en diferentes plataformas (Windows, HTML). Aunque los botones deben tener la misma funcionalidad (hacer clic), su presentación y comportamiento específico varía según la plataforma. El Factory Method permite:

- Encapsular la creación de objetos
- Desacoplar el código cliente de las clases concretas
- Añadir nuevas plataformas sin modificar el código existente

