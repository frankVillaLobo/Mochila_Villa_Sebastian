# Cheatsheet de Comandos Git

## Configuración

Configurar nombre de usuario:
`git config --global user.name "Tu Nombre"`

Configurar dirección de correo electrónico:
`git config --global user.email "tucorreo@example.com"`

## Iniciar Repositorio

Iniciar un nuevo repositorio:
`git init`

Clonar un repositorio existente:
`git clone <url_del_repositorio>`

## Realizar Cambios

Verificar el estado de los archivos:
`git status`

Crear un nuevo commit con los cambios:
`git commit -m "Mensaje del commit"`

## Ramas (Branches)

Listar todas las ramas del repositorio:
`git branch`

Crear una nueva rama:
`git branch <nombre_rama>`

Cambiar a una rama existente:
`git checkout <nombre_rama>`

Eliminar una rama:
`git branch -d <nombre_rama>`

## Sincronización Remota

Listar los repositorios remotos:
`git remote -v`

Agregar un nuevo repositorio remoto:
`git remote add <nombre_remoto> <url_del_repositorio>`

Enviar cambios locales a un repositorio remoto:
`git push <nombre_remoto> <nombre_rama>`

Obtener cambios de un repositorio remoto:
`git pull <nombre_remoto> <nombre_rama>`

## Historial y Diferencias

Ver el historial de commits:
`git log`

Ver los cambios realizados en un archivo:
`git diff <nombre_archivo>`
