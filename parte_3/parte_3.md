# Parte 3

## 1. Analiza

    git status
    git add README.md
    git commit -m "Actualiza documentación"
    git push

El primer comando muestra el estado de los archivos (si están guardados o no), con el add es que, en estecaso README.md, se guardan y se preparan para crear una versión, que es dada por commit -m. Finalmente push sube la versión creada al repositorio en GitHub.

## 2. Identifica qué falta

Caso A
    Modificar archivo
    ↓
    git add .
    ↓
    git commit -m "nombre/descripción_versión" // Falta //
    ↓
    git push

    No se puede hacer un push si no hay una versión gardada que subir a la nube.

Caso B
    Repositorio GitHub
    ↓
    git clone "link_del_repositorio"/git pull // Falta //
    ↓
    Repositorio local

    No se puede pasar la información de un repositorio en la nube al local sin cualquiera de esos dos comandos.

Caso C
    Repositorio remoto actualizado
    ↓
    git pull // Falta //
    ↓
    Repositorio local actualizado

    Para bajar los cambios de GitHub al repositorio local, se debe utilizar el comando git pull.