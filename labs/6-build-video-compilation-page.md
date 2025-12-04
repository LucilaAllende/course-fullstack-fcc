## 🎬 Taller: Construcción de una Página de Compilación de Videos Temática

### 🎯 Objetivo del Proyecto
El objetivo de este laboratorio es construir una página web organizada para presentar una **compilación de contenido en video** sobre un tema específico de tu elección (música, ciencia, historia, etc.). Deberás utilizar los elementos semánticos de HTML, enfocándote en la correcta estructuración y el uso del elemento `<iframe>` para incrustar los videos.

### ✅ Historias de Usuario (Requisitos Funcionales)

Para completar el proyecto, la estructura de la página debe adherirse a los siguientes puntos:

#### 1. Estructura Principal y Semántica
* El elemento **`<body>`** debe contener **únicamente** un elemento **`<main>`** como su hijo directo, asegurando una estructura semántica clara.
* Dentro de `<main>`, debe haber un elemento **`<h1>`** que establezca el **tópico principal** de la página (ej: "Grandes Misterios del Universo").
* Inmediatamente debajo del `<h1>`, debe haber un elemento **`<p>`** introduciendo el tema de la compilación.
* Debajo del párrafo introductorio, la página debe contener **tres elementos `<section>`**.

#### 2. Bloques de Contenido de Video (Repetidos 3 Veces)
Cada uno de los tres elementos `<section>` debe contener los siguientes elementos **en este orden exacto**:

1.  Un elemento **`<h2>`** (Título del video/subsección).
2.  Un elemento **`<p>`** (Breve descripción o contexto del video).
3.  Un elemento **`<iframe>`** (El video incrustado).

#### 3. Requisitos del `<iframe>`
Cada uno de los tres elementos `<iframe>` debe incluir los siguientes atributos:

* **`src`**: Debe apuntar a una **URL de video válida** (ej: un enlace de incrustación de YouTube o Vimeo).
* **`title`**: Un atributo descriptivo para la accesibilidad, detallando el contenido incrustado.
* **`height` y `width`**: Atributos definidos para establecer un tamaño adecuado y consistente para el reproductor.

---
