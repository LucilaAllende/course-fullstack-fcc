## 🔍 Taller de Debugging: Rescatando el Blog de Camperbot

### 🎯 El Desafío
Camperbot ha lanzado su blog de aprendizaje, pero tiene un gran problema: **no es accesible para todos**. El código actual contiene malas prácticas de estructura y errores de jerarquía que confunden a los lectores de pantalla y afectan el SEO. 

Tu misión es realizar una "cirugía de código" para transformar este sitio en una página web inclusiva, semántica y profesional.

### 🛠️ ¿Qué vamos a diagnosticar y reparar?

En este taller, te convertirás en un experto en **Accesibilidad Web (A11y)** atacando los siguientes puntos críticos:

1.  **Jerarquía de Encabezados (Heading Level Spacing):**
    * Aprenderás por qué nunca debemos saltar de un `<h1>` a un `<h4>` o usar múltiples `<h1>`. Reorganizaremos la estructura para que los niveles (H1 -> H2 -> H3) tengan sentido lógico.
    
2.  **Semántica de Contenedores:**
    * Sustituiremos los genéricos `<div>` por etiquetas con significado real como **`<article>`**, **`<section>`** y **`<nav>`**, permitiendo que el navegador entienda dónde termina la navegación y dónde empieza el contenido.

3.  **Navegación y Landmark Roles:**
    * Optimizaremos la lista de navegación para que sea identificada correctamente como el menú principal del sitio.

4.  **Información de Contacto y Pie de Página:**
    * Utilizaremos etiquetas específicas para que los datos de contacto sean detectables programáticamente.



### 💡 ¿Por qué es importante?
Un código "limpio" no es solo el que se ve bien en el navegador, sino el que es **perceptible y navegable para todos**. Al corregir el blog de Camperbot, estarás asegurando que su mensaje llegue a cada rincón de la web, sin barreras.

---