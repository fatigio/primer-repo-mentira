git config --global user.name "name"
git config --global user.email mail

Para ver que usuario y mail tengo:
git config --list 

Paso 1:
Crear un repositorio: git init

Paso 2:
Dar seguimiento a los archivos de nuestro repositorio de a uno: git add <nombre>
Todos juntos: git add .

Ver como estan los archivos: git status

.gitignore: dentro ponemos los archivos o carpetas que no se quieren subir al repositorio

El area de preparacion esta pensada para hacer cambios

Paso 3:
Crear una version (commit) del repositorio
git commit -m "Version 1 de mi repositorio"

git log: registro de los commits que se fueron haciendo

Paso 4:
Renombra la rama master a main:
git branch -M main

Paso 5:
Conectar nuestro repo local con un origen remoto:
git remote add origin https://github.com/fatigio/primer-repo-mentira.git

Paso 6:
Subir nuestros cambios al repositorio remoto
git push -u origin main

PASOS PARA ACTUALIZAR EL PROYECTO

Paso 1:
Añadimos los cambios
git add .

Paso 2:
Hacer una nueva version 
git commit -m "describi los cambios brevemente"

Paso 3:
Subir la version 
git push