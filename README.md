# Catálogo de Revistas en C#

Este proyecto es una aplicación de consola en **C#** que permite gestionar un catálogo de revistas y realizar búsquedas dentro de él utilizando un **algoritmo recursivo**.

## Funcionalidades
- Almacena un catálogo con **10 revistas predeterminadas**.
- Menú interactivo con las siguientes opciones:
  1. Buscar una revista por título.
  2. Mostrar todas las revistas en el catálogo.
  3. Salir del programa.
- La búsqueda se realiza de forma **recursiva** e ignora mayúsculas/minúsculas.
- Mensajes de salida:
  - `"Encontrado"` → si la revista existe en el catálogo.
  - `"No encontrado"` → si la revista no está.

## Tecnologías usadas
- Lenguaje: **C#**
- Entorno: **.NET Console Application**

## Requisitos
- Tener instalado **.NET SDK** en tu computadora.  
  Puedes verificarlo con:
  ```bash
  dotnet --version
