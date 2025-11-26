## 🗺️ Construye una Página de Agencia de Viajes

**Objetivo del Proyecto:** Crear una aplicación funcionalmente similar al proyecto de ejemplo, pero con tu **estilo personal**. No copies el ejemplo, ¡sé creativo!

El objetivo es cumplir con las siguientes **Historias de Usuario** y **superar todas las pruebas** del laboratorio.

---

### ✅ Historias de Usuario Requeridas

#### **Estructura Básica del Documento (HTML)**

* Debes incluir la declaración `DOCTYPE`.
* Debes tener un elemento `<html>` con el atributo `lang` establecido en **`en`**.
* Debes tener un elemento `<head>` que contenga:
    * Un elemento **`meta` void** con `charset` establecido en **`utf-8`**.
    * Un elemento `<title>` con el texto **`Travel Agency Page`**.
    * Una etiqueta `meta` adicional para **SEO** que contenga una **descripción corta** de tu sitio web (atributo `name="description"` y `content="..."`).

#### **Contenido Principal - Introducción**

* Debes tener un elemento `<h1>` para presentar tus **destinos de viaje**.
* Debes tener un elemento `<p>` justo debajo del `<h1>` introduciendo las **oportunidades de viaje**.

---

### 🧳 Sección de Paquetes

* Debes incluir un elemento `<h2>` con el texto **`Packages`**.
* Debes tener un elemento `<p>` que introduzca brevemente los **diversos paquetes**.
* Debes incluir un elemento de **lista desordenada** (`<ul>`) con **dos** elementos de lista (`<li>`).
    * Los dos elementos de lista deben tener el texto **`Group Travels`** y **`Private Tours`**, respectivamente.
    * El texto de cada `<li>` debe estar **encerrado por un elemento ancla** (`<a>`).

---

### 📸 Sección de Itinerarios Principales

* Debes tener un elemento `<h2>` con el texto **`Top Itineraries`**.
* Debes tener al menos **tres** elementos `<figure>`.
    * Cada `<figure>` debe contener un **elemento ancla** (`<a>`) y un elemento **`figcaption`**.

#### **Imágenes y Enlaces**

* Los **tres elementos ancla** dentro de los `<figure>` deben contener un elemento `<img>` como su contenido.
    * Cada `<img>` debe tener un atributo **`alt` apropiado** y un atributo **`src`** establecido a una imagen válida.
    * **Imágenes sugeridas (opcional):**
        * `https://cdn.freecodecamp.org/curriculum/labs/colosseo.jpg`
        * `https://cdn.freecodecamp.org/curriculum/labs/alps.jpg`
        * `https://cdn.freecodecamp.org/curriculum/labs/sea.jpg`
* **Todos tus cinco elementos ancla** (los dos en la lista y los tres en los *figures*) deben cumplir con:
    * Tener el atributo **`href`** con el valor **`https://www.freecodecamp.org/learn`**.
    * Tener el atributo **`target`** con el valor **`_blank`**.