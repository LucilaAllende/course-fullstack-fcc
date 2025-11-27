# 🛠️ Depuración: Página de Adopción de Mascotas

---

## 📝 Descripción del Problema

**Sally**, propietaria de una tienda de adopción de mascotas, ha construido su primera página web, pero existen **errores críticos** en el código que impiden su correcto funcionamiento.

Tu misión es **corregir todos los errores** detallados a continuación para que Sally pueda continuar con el desarrollo de su página.

**Objetivo:** Cumplir con las historias de usuario y lograr que todas las pruebas pasen.

---

## ✅ Errores a Corregir (Historias de Usuario)

### 1. Elemento de Imagen (`<img>`)

Sally quiere usar una imagen de gatos, pero no se está mostrando correctamente. Debes corregir lo siguiente en el elemento `<img>`:

* **Fuente:** Reemplazar el atributo **`href`** por el atributo correcto para la fuente de la imagen: **`src`**.
* **Texto Alternativo:** Reemplazar el atributo **`att`** por el atributo correcto para el texto descriptivo corto: **`alt`**.
* **Etiqueta de Cierre:** Eliminar la etiqueta de cierre **`</img>`** (los elementos `<img>` son *void elements* y no la necesitan).

### 2. Elementos de Enlace (`<a>`)

Los enlaces a las páginas de perros y gatos no están funcionando. Debes corregir lo siguiente en ambos elementos `<a>`:

* **URL de Destino:** Reemplazar el atributo **`src`** por el atributo correcto para especificar la URL de destino de un enlace: **`href`**.

---

### 💡 Recordatorio de Sintaxis

| Elemento | Uso Correcto | ¿Qué hace? |
| :--- | :--- | :--- |
| `<img>` | `<img **src**="ruta.jpg" **alt**="Descripción">` | Incrusta una imagen (usa **`src`**). |
| `<a>` | `<a **href**="pagina.html">Link</a>` | Crea un hipervínculo (usa **`href`**). |