# 👩‍🍳 Requisitos del Proyecto: Aplicación de Recetas

---

## 🎯 Objetivo Principal

Construir una aplicación funcionalmente similar al proyecto de ejemplo, pero con un estilo y diseño **personal y único**.

---

## ✅ Historias de Usuario (Requisitos de Código)

**Objetivo:** Cumplir con todos los requisitos a continuación y obtener la aprobación de las pruebas del laboratorio.

### 🏗️ 1. Estructura y Metadatos de la Página

* Debe incluir la declaración **`<!DOCTYPE html>`**.
* Debe tener un elemento **`<html>`** con el atributo `lang` establecido en **`en`**.
* El elemento **`<head>`** debe contener:
    * Un elemento **`<title>`** con el nombre de tu receta.
    * Un elemento **`<meta>`** con el atributo `charset` establecido en **`UTF-8`**.
* Debe incluir el elemento **`<body>`**.

### 🧱 2. Contenido Principal y Jerarquía

* Debe haber un elemento **`<h1>`** con el nombre de tu receta.
* Debe haber un elemento **`<p>`** de introducción para la receta, ubicado justo debajo del `<h1>`.
* Debe haber un elemento **`<h2>`** con el texto **"Ingredientes"**.

### 📋 3. Secciones de la Receta

* **Ingredientes:** Debes usar una **lista no ordenada** (`<ul>`) con al menos **cuatro elementos de lista** (`<li>`) con la lista de ingredientes (ubicada después del primer `<h2>`).
* **Instrucciones:**
    * Debes tener un segundo elemento **`<h2>`** con el texto **"Instrucciones"**.
    * Debes usar una **lista ordenada** (`<ol>`) con al menos **cuatro elementos de lista** (`<li>`) para listar los pasos de la receta (ubicada después del segundo `<h2>`).

### 🖼️ 4. Elemento de Imagen

* Debes incluir un elemento **`<img>`** con los siguientes atributos:
    * Un atributo **`src`** establecido a una imagen válida (Ejemplo opcional: `https://cdn.freecodecamp.org/curriculum/labs/recipe.jpg`).
    * Un atributo **`alt`** que describa el contenido de la imagen.
