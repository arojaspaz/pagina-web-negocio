## Bienvenido al repositorio
## Instalación SASS
Debes tener instalado SASS globalmente.  Sass es un preprocesador CSS que convierte archivos .scss a archivos .css.
Puedes instalar Sass globalmente utilizando npm (Node Package Manager) si tienes Node.js
Abre tu terminal o símbolo del sistema y ejecuta el siguiente comando: <br>
*npm install -g sass*

## Compilación de archivos SASS
Ahora para que el preprocesador SASS escuche y compile los cambios o las mejoras  😃 que vayas a realizar, solo tienes que ejecutar
el siguiente comando en el path del proyecto: <br>
*sass src/main.scss public/css/main.css --watch*

## Notas a tener en cuenta
En las animaciones se usa la propiedad "*animation-timeline*", la cual no es soportada por todos los navegadores, por lo que se recomienda
utilizar polyfills para asegurarse de que todos los navegadores incluir estas animaciones.