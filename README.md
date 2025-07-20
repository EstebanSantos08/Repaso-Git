# Repaso-Git


Crear y clonar repositorios

git init - Inicializar un repositorio nuevo
git clone <url> - Clonar un repositorio existente

Comandos básicos del flujo de trabajo

git status - Ver el estado actual del repositorio
git add <archivo> - Agregar archivo al staging area
git add . - Agregar todos los archivos modificados
git commit -m "mensaje" - Crear un commit con mensaje
git push - Subir cambios al repositorio remoto
git pull - Descargar y fusionar cambios del repositorio remoto

Manejo de ramas (branches)

git branch - Listar ramas locales
git branch <nombre> - Crear nueva rama
git checkout <rama> - Cambiar a una rama
git checkout -b <rama> - Crear y cambiar a nueva rama
git merge <rama> - Fusionar una rama con la actual
git branch -d <rama> - Eliminar rama local

Historial y información

git log - Ver historial de commits
git log --oneline - Historial resumido en una línea por commit
git diff - Ver diferencias en archivos modificados
git show <commit> - Mostrar detalles de un commit específico

Deshacer cambios

git checkout -- <archivo> - Descartar cambios en un archivo
git reset <archivo> - Quitar archivo del staging area
git reset --hard HEAD - Descartar todos los cambios no committeados

Repositorios remotos

git remote -v - Ver repositorios remotos configurados
git remote add origin <url> - Agregar repositorio remoto
git fetch - Descargar cambios sin fusionar

Estos comandos cubren aproximadamente el 90% de las operaciones que realizarás con Git en proyectos típicos.ReintentarClaude puede cometer errores. Verifique las respuestas.
