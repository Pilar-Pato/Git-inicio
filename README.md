# Git-inicio
Step 1:
Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.

> git config --global user.name "Your-Full-Name"
> git config --global user.email "your-email-address"
> git config --global color.ui auto
> git config --list
Step 2:
Crear un repositorio nuevo vacío en Github con el nombre “Libro”.

Desde el terminal:
> cd <nombre de la carpeta a la que se quiera acceder> (ejemplo: cd Documents/)
> mkdir libro
> cd libro
> touch .gitignore
> touch README.md
> git init
> ls -la
> git add .
> git commit -m “initialized repository”
> git branch -m main

Conectar el proyecto creado con el repositorio “Libro” de Github creado al principio (Instrucciones en Github)

> git remote add origin <la url de tu repositorio>

Realiza la subida del proyecto al repositorio utilizando el siguiente comando:

> git push -u origin main

Step 3:

Comprobar el estado del repositorio. 
Crear un fichero index.txt (en local) con el siguiente contenido:
Capítulo 1: Introducción a Git
Capítulo 2: Flujo de trabajo básico
Capítulo 3: Repositorios remotos
Comprobar de nuevo el estado del repositorio.
Añadir el fichero a la zona de intercambio temporal. (staging area)
Volver a comprobar una vez más el estado del repositorio.
Realizar el commit
Volver a comprobar una vez más el estado del repositorio.
Subir los cambios al repositorio remoto
Entrega en classroom el enlace del repositorio.

> git status
> cat > index.txt
Capítulo 1: Introducción a Git
Capítulo 2: Flujo de trabajo básico
Capítulo 3: Repositorios remotos
> git status
> git add indice.txt
> git status
> git commit -m “added index.txt”
> git status
> git push
