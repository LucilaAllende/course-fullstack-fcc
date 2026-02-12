## 📅 Laboratorio: Construcción de un Centro de Eventos (Event Hub)

### 🎯 Objetivo del Proyecto
El desafío de este laboratorio es diseñar y estructurar un **Centro de Eventos** dinámico utilizando **HTML Semántico**. El objetivo es crear una arquitectura de información sólida que permita a los usuarios navegar entre eventos futuros y pasados, dándole tu propio estilo visual y personalidad al proyecto.

### 🛠️ Lo que Construirás y Aprenderás

Dominarás la organización de contenido complejo mediante las siguientes historias de usuario:

#### 1. Cabecera y Navegación Inteligente
* **`header` Global:** Crearás una cabecera que incluya el título principal `<h1>Event Hub` y un área de navegación (`<nav>`).
* **Menú de Anclas:** Implementarás una lista desordenada con enlaces directos (`#upcoming-events` y `#past-events`) para mejorar la usabilidad mediante navegación interna.

#### 2. Estructura de Contenido Principal (`<main>`)
Dentro del núcleo de la página, organizarás la información en dos grandes bloques:

* **🚀 Sección de Próximos Eventos (`#upcoming-events`):**
    * Utilizarás elementos **`<article>`** para encapsular cada evento como una unidad independiente.
    * Cada evento contará con su título (`<h3>`) y una descripción detallada (`<p>`).

* **📜 Sección de Eventos Pasados (`#past-events`):**
    * Similar a la anterior, pero enriquecida con **contenido visual**.
    * Cada artículo incluirá una **imagen descriptiva** con sus respectivos atributos `src` y `alt`, proporcionando un registro histórico visual de los eventos.

### 💡 Puntos Clave de Semántica
* **`article` vs `section`:** Aprenderás cuándo un evento tiene suficiente entidad para ser un artículo independiente.
* **Accesibilidad:** Uso correcto de atributos `alt` en imágenes y jerarquía de encabezados (`h1` -> `h2` -> `h3`).

---