# Gestor de Prompts AI - v3 (Colores Personalizados)

![Logo Placeholder](https://drive.google.com/file/d/1GJwQ_J0QO19FsHHzstIxYyKrGKROID1N/view?usp=drive_link)


Una herramienta web local para crear, gestionar y perfeccionar tus prompts para interactuar con modelos de Inteligencia Artificial. Construida con HTML, Tailwind CSS y JavaScript puro, utilizando `localStorage` para almacenar los datos directamente en tu navegador.

## Descripción

Este gestor te permite organizar tus prompts más efectivos, crear nuevos siguiendo una estructura guiada y tener siempre a mano tus mejores interacciones con IA. Al ser un archivo HTML local, tus datos permanecen privados en tu computadora.

## Características Principales (v3)

* **Creación y Edición Estructurada:** Formulario detallado basado en principios de ingeniería de prompts (Rol, Contexto, Tarea, Formato, Tono, etc.).
* **Biblioteca Local:** Guarda y organiza tus prompts en el almacenamiento local de tu navegador.
* **Búsqueda y Filtrado:** Busca por nombre, categoría, etiqueta o contenido. Filtra por favoritos y etiquetas activas.
* **Etiquetado Múltiple (Tags):** Asigna múltiples etiquetas a tus prompts para una organización flexible.
* **Categorías:** Asigna una categoría principal a cada prompt.
* **Calificación y Uso:** Califica tus prompts (1-5 estrellas) y lleva un registro de cuántas veces has copiado el prompt final.
* **Variaciones:** Guarda múltiples versiones de un prompt final bajo un mismo prompt principal.
* **Detección de Placeholders:** Identifica marcadores como `[variable]` o `{variable}` en tus prompts finales y te permite rellenarlos fácilmente antes de copiar.
* **Importar/Exportar:**
    * Exporta todos tus prompts o una selección a un archivo JSON.
    * Importa prompts desde un archivo JSON (con opción de fusionar o reemplazar).
* **Gestión de Etiquetas/Categorías:** Renombra o elimina etiquetas y categorías existentes (actualizando los prompts asociados).
* **Favoritos:** Marca tus prompts más importantes para un acceso rápido.
* **Duplicar Prompt:** Crea fácilmente una copia de un prompt existente.
* **Tema de Color Personalizado:** Interfaz adaptada con una paleta de colores específica.
* **Recordatorio de Backup:** Sugiere exportar los datos periódicamente.

## ¿Cómo Usarlo?

1.  **Descarga:** Descarga el archivo `.html` (por ejemplo, `gestor_prompts_v3_colors.html`) de este repositorio.
2.  **Abre:** Haz doble clic en el archivo descargado. Se abrirá en tu navegador web predeterminado (Chrome, Firefox, Edge, Safari, etc.).
3.  **Utiliza:** ¡Empieza a crear y gestionar tus prompts! Tus datos se guardarán automáticamente en el `localStorage` de ese navegador en tu computadora.

**Importante:** Como los datos se guardan en el `localStorage` del navegador, son específicos de ese navegador y de ese perfil de usuario en tu computadora. Si limpias la caché o los datos del sitio del navegador, podrías perder tus prompts. **Utiliza la función de "Exportar Todo" regularmente para hacer copias de seguridad.**

## Capturas de Pantalla







## Tecnologías Utilizadas

* **HTML5:** Estructura del contenido.
* **Tailwind CSS:** Framework CSS para el diseño y estilos rápidos.
* **JavaScript (ES6+):** Lógica de la aplicación, manipulación del DOM y gestión del `localStorage`.
* **Font Awesome:** Biblioteca de iconos.

## Planes Futuros

La intención es evolucionar esta herramienta para ofrecer almacenamiento en la nube y potencialmente características colaborativas. El siguiente gran paso planeado es:

* **Integración con Firebase:**
    * Utilizar Firestore para almacenar los prompts en la nube de forma segura.
    * Implementar autenticación de usuarios (Firebase Auth) para que cada usuario tenga su propia biblioteca privada accesible desde cualquier lugar.
    * Explorar Cloud Functions para posibles lógicas adicionales en el futuro.

## Contribuciones

Por el momento, este es un proyecto personal. Sin embargo, las sugerencias y reportes de errores son bienvenidos a través de las "Issues" de GitHub.

## Licencia

*(Opcional: Añade aquí la licencia que prefieras, por ejemplo, MIT)*



MIT License
Copyright (c) [2025] [JavierValencia_GestorPrompts]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
