# Readme basico para Node.js

## ¿Qué contiene este plantilla?
Este repositorio cuenta inicialmente con la sigueinte estrucutra:

- `.github/workflows` Contiene los workflows esablecidos para seguir los lineamientos Devops definidos por la organización.
- `githooks` Contiene acciones que se ejecutan a nivel local de cada desarrollador que validan determinados aspectos para que los workflows de Devops se ejecuten de forma satisfactoria. Estos no funcionan por si solos, y es necesario que los desarrolladores ejecuten el comando `git config --global core.hooksPath` una vez dentro de su pc.
- `src` Esta carpeta deberá contar con toda la estrucutra del proyecto, inicialmente cuenta con el archivo `index.js` el cual debe ser el punto de entrada de la aplicación, modificar el nombre de este archivo o modificar su ubicación puede generar graves conflictos en la ejecución de workflows.
- `.gitignore` Este archivo contiene la definicion de archivos basicos que no seran trackeados en la hisotria de git, este archivo puede modificarse segun las necesidades del equipo de desarrollo.
- `package.json` Este archivo cuenta con las definiciones basicas de un proyecto de node.js, en el se encuentran configuradas las librerias necesarias para la realización de pruebas unitarias y se encuentran configurados los comandos `npm test` para la ejecucion de pruebas unitarias y `npm start` para la ejecución del proyecto.
- `readme.md` este archivo debe contener información relevante al proyecto, este contenido sera el primero que se observará al ingresar al repositorio.
