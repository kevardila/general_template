# Readme basico para JAVA

## ¿Qué contiene este plantilla?
Este repositorio cuenta inicialmente con la sigueinte estrucutra:

- `.github/workflows` Contiene los workflows esablecidos para seguir los lineamientos Devops definidos por la organización.
- `githooks` Contiene acciones que se ejecutan a nivel local de cada desarrollador que validan determinados aspectos para que los workflows de Devops se ejecuten de forma satisfactoria. Estos no funcionan por si solos, y es necesario que los desarrolladores ejecuten el comando `git config --global core.hooksPath` una vez dentro de su pc.
- `.gitignore` Este archivo contiene la definicion de archivos basicos que no seran trackeados en la hisotria de git, este archivo puede modificarse segun las necesidades del equipo de desarrollo.
- `readme.md` este archivo debe contener información relevante al proyecto, este contenido sera el primero que se observará al ingresar al repositorio.
