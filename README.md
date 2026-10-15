# 🌐 Curso Práctico de HTML5 Básico

¡Bienvenido a este repositorio de aprendizaje! Este espacio está dedicado al almacenamiento, organización y desarrollo de ejercicios prácticos basados en los fundamentos de **HTML5** (HyperText Markup Language).

---

## 📁 Estructura del Proyecto

El repositorio está estructurado de manera modular para separar los recursos visuales de las sesiones de aprendizaje práctico:

*   **`img/`**: Carpeta destinada a almacenar el material gráfico y logotipos utilizados en los ejercicios (formatos modernos `.webp`).
*   **`index.html`**: Archivo principal en la raíz del espacio de trabajo que funciona como el portal o índice general.
*   **`sesion-2/`**: Bloque enfocado en la segunda sesión de clases y laboratorios:
    *   **`Exercise01/`**: Primer ejercicio práctico de maquetación independiente con su respectivo `index.html`.
    *   **`Exercise02/`**: Segundo ejercicio estructurado con subcarpetas internas (`pages/`) para practicar rutas relativas complejas.
*   **`.vscode/`**: Configuraciones locales del editor para mantener la consistencia en el formateo de código.

---

## 📚 Conceptos Técnicos Aplicados

A través de la arquitectura de este árbol de directorios, se ponen en práctica los siguientes pilares de la [Introducción a HTML en MDN Web Docs](https://mozilla.org "Documentación de Sintaxis Básica de HTML"):

1.  **Rutas Relativas**: Enlace correcto de activos desde carpetas externas (ej. `<img src="img/HTML5_logo_and_wordmark.webp">`).
2.  **Enrutamiento entre Páginas**: Navegación interna navegando desde el índice de la raíz hacia las subcarpetas de los ejercicios prácticos.
3.  **Modularidad**: Segmentación de código en entornos aislados por nivel de dificultad o sesión de estudio.

---

## 🛠️ Instrucciones de Uso Local

Para explorar y ejecutar cualquiera de estos ejercicios en tu entorno de desarrollo:

1.  Asegúrate de abrir la carpeta raíz **`mi-proyecto`** utilizando tu editor de código de preferencia (recomendado [Visual Studio Code](https://code.visualstudio.com/ "Descargar VS Code")).
2.  Para iniciar la visualización, haz clic derecho sobre el archivo `index.html` que desees revisar y selecciona **Open with Live Server** (en caso de contar con la extensión instalada) o simplemente arrastra el archivo hacia la pestaña de tu navegador web habitual.

---

## 📝 Notas de Configuración
El proyecto incluye un archivo `.gitattributes` para asegurar el procesamiento adecuado y la preservación de saltos de línea consistentes entre los colaboradores de Git que utilicen diferentes sistemas operativos (Windows, Mac o Linux).