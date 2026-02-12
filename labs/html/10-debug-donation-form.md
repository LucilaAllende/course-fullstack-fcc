# 🛠️ Depuración de Laboratorio: Formulario de Donación

Una organización benéfica local ha creado un sitio web con un formulario de donación, pero presenta varios problemas técnicos y de accesibilidad. Tu misión es refactorizar el código para asegurar que cumpla con los estándares web modernos y sea utilizable para todas las personas.

### 📋 Objetivos
Corregir todos los errores de sintaxis HTML e implementar las mejores prácticas de accesibilidad siguiendo las historias de usuario detalladas a continuación.

---

### 🚀 Historias de Usuario

1. **Limpieza de Sintaxis**
   * Los elementos `input` son **elementos vacíos** (void elements).
   * *Acción:* Elimina todas las etiquetas de cierre `</input>` del formulario.

2. **Identificación de Campos**
   * Cada campo de entrada necesita un propósito claro.
   * *Acción:* Agrega elementos `<label>` para cada campo, asegurando que el texto de la etiqueta coincida con la descripción actual junto al input.

3. **Corrección de Tipos de Datos**
   * El campo "Email Address" debe validar específicamente formatos de correo electrónico.
   * *Acción:* Cambia el atributo `type` de `text` a `email`.

4. **Establecer Relaciones (Accesibilidad)**
   * Los lectores de pantalla deben saber qué etiqueta pertenece a cada entrada.
   * *Acción:* Asocia cada elemento `label` con su `input` correspondiente usando el atributo `for` en la etiqueta y un atributo `id` coincidente en el input.

5. **Validación de Datos Obligatorios**
   * Ciertos campos son obligatorios para procesar la donación.
   * *Acción:* Agrega el atributo `required` a los campos de **texto**, **email** y **número** (no lo agregues al checkbox ni al botón de envío).

---

### 🧪 Validación
Una vez aplicadas las correcciones, haz clic en **"Run the Tests"** para verificar que el formulario sea totalmente funcional y accesible.