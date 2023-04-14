# Entornos-GRUPO4
## Entornos-GRUPO4
## MENSAJE PARA LOS DEVELOPPERS!!!
* LA IDEA ES HACER UN GIT CLONE.
* COGER ESTE CODIGO COMO BASE ESTRUCTURAL.
* GENERAR UNA RAMA NUEVA QUE SE LLAME GRUPO_4-"TU_NOMBRE"
* DESARROLLAR TU PROYECTO APROVECHANDO LA ESTRUCTURA BASICA
* PUSHEAR EL PROYECTO PERSONAL TERMINADO
* 'er jefe' hará un merge de las ramas hacia en main

## Recordatorio de comandos básicos de GIT
# Configuracion inicial
# Configurar el nombre de usuario
git config --global user.name "Tu nombre"

# Configurar el correo electrónico
git config --global user.email "tu@email.com"

# Configurar el editor de texto preferido
git config --global core.editor "nombre_del_editor"

# Iniciar un nuevo repositorio local
git init

# Clonar un repositorio remoto
git clone <URL_del_repositorio>

# Verificar el estado de los archivos
git status

# Agregar archivos para ser rastreados
git add <nombre_del_archivo>

# Agregar todos los archivos modificados para ser rastreados
git add .

# Confirmar los cambios
git commit -m "Mensaje del commit"

# Verificar el historial de commits
git log

# Crear una nueva rama
git branch <nombre_de_la_rama>

# Cambiar a una rama específica
git checkout <nombre_de_la_rama>

# Fusionar una rama con la rama actual
git merge <nombre_de_la_rama>

# Actualizar y obtener cambios del repositorio remoto
git pull

# Subir cambios al repositorio remoto
git push origin <nombre_de_la_rama>
