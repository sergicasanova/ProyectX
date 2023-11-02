# ProyectX
En este proyecto de desarrollo de una página web que enseña JavaScript aplicado a interacciones con elementos HTML, se ha utilizado un sistema de control de versiones (Git) y se ha seguido una metodología de desarrollo colaborativo (GitFlow). Aquí está un resumen de los pasos clave:

Introducción Teórica: Se proporcionó una introducción teórica sobre Git y la importancia de seguir una metodología de desarrollo en el trabajo colaborativo. Se mencionó GitFlow como una posible metodología.

Creación del Repositorio: Se creó un repositorio en GitHub con las ramas "master" y "develop".

Configuración Inicial: Se instaló el boilerplate HTML5 en el repositorio y se realizaron configuraciones necesarias, como cambiar la versión de Node y ejecutar el proyecto.

Usuario 1 - Creación de la Estructura Inicial: El usuario 1 creó el esqueleto de la página web en la rama "feature/first-layout" y realizó el primer commit con el mensaje convencional. Luego, hizo un merge con la rama "develop" para que otros puedan comenzar a trabajar.

Usuario 2 - Creación de Features: El usuario 2 creó dos ramas de características: "feature/contenidoHTML" y "feature/atributosHTML". En la rama "contenidoHTML", implementó ejemplos de modificación de contenido HTML. En la rama "atributosHTML", implementó ejemplos de modificación de atributos HTML. Subió sus cambios al repositorio.

Usuario 3 - Creación de Feature: El usuario 3 creó una rama "feature/estilosCSS" y agregó ejemplos de modificación de estilos CSS. Luego, subió sus cambios y se hizo un merge en la rama "develop".

Usuario 1 - Pruebas y Etiquetado: El usuario 1 cambió a la rama "master", etiquetó la versión como "v1.0", y creó una rama "test" para que los probadores verifiquen el desarrollo.

Hooks de Git: El usuario 1 automatizó algunos procesos mediante hooks de Git. Estos incluyeron la recreación de la carpeta "node_modules" al clonar el proyecto y la verificación del formato del mensaje de commit. También se configuró un linter (ESLint) para verificar el formato de los archivos HTML.

Carpeta gitHooks: Los hooks de Git se almacenaron en una carpeta "gitHooks" dentro del proyecto y se fusionaron en la rama "develop" para que todos los miembros del equipo puedan acceder a ellos.

Este enfoque organizado y documentado demuestra una metodología de desarrollo colaborativo sólida y buenas prácticas en el uso de control de versiones para garantizar la calidad del proyecto.