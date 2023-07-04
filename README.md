# Curso de **Git & GitHub**

Hola soy Luis Ricci, alumno de Jonathan MirCha aprendiendo este maravilloso mundo de la Programación.

## Flujo básico de Git & GitHub

Agregar los cambios de un archivo al staged

- git add archivo/directorio

agregar todos los cambios de todos los archivos al staged

- git add .

Los cambios son comprometidos en el repositorio debes escribir el mensaje del cambio cuando se abra el archivo de configuración al terminar guarda y cierra el archivo para que los cambios tengan efecto

- git commit

Es un shortcut del comando anterior escribes y confirmas el mensaje del cambio en un sólo paso

- git commit -m "mensaje descriptivo del cambio"

Se agrega el origen remoto de tu repositorio de GitHub

- git remote add origin https://github.com/usuario/repositorio.git

La primera vez que vinculamos el repositorio remoto con el local

- git push -u origin master

Para las subsecuentes actualizaciones, sino cambias de rama

- git push

Para descargar los cambios del repositorio remoto al local

- git pull
