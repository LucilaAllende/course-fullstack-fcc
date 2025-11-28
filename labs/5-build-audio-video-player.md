## 🎬 Taller: Construcción de un Reproductor Multimedia HTML Nativo

### 🎯 Objetivo del Proyecto
El objetivo de este laboratorio es construir una aplicación que integre y gestione contenido multimedia de audio y video utilizando las etiquetas HTML nativas. Deberás crear una interfaz sencilla pero completa que cumpla con todos los requisitos funcionales a continuación, dándole tu propio toque de **diseño y estilo**.

### ✅ Historias de Usuario (Requisitos Funcionales)

El proyecto debe estar estructurado en dos secciones principales, una para video y otra para audio:

#### 1. Estructura General y Encabezados
* Debe contener un elemento **`<h1>`** para el título principal de la página.
* El contenido se debe dividir en **dos elementos `<section>`**.

#### 2. Sección de Video
* **Encabezado:** Debe tener un elemento **`<h2>`** para el título específico del video en reproducción.
* **Elemento `video`:**
    * Debe incluir la etiqueta **`<video>`** con el atributo **`controls`** habilitado.
    * El atributo **`width`** debe estar establecido en **`640`** píxeles.
* **Fuente del Video:** Dentro del elemento `<video>`, debe haber un elemento **`<source>`** con:
    * Atributo **`src`** apuntando a un archivo de video válido.
    * Atributo **`type`** especificando el tipo MIME (ej: `video/mp4`).
* ***Sugerencia de Fuente de Video:*** `https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.mp4`

#### 3. Sección de Audio
* **Encabezado:** Debe tener un elemento **`<h2>`** para el título de la canción o audio en reproducción.
* **Elemento `audio`:**
    * Debe incluir la etiqueta **`<audio>`**.
    * Debe tener los atributos **`controls`** y **`loop`** habilitados.
    * El atributo **`src`** debe apuntar directamente a un archivo de audio válido.
* ***Sugerencias de Fuentes de Audio:***
    * `https://cdn.freecodecamp.org/curriculum/js-music-player/sailing-away.mp3`
    * `https://cdn.freecodecamp.org/curriculum/js-music-player/we-are-going-to-make-it.mp3`
