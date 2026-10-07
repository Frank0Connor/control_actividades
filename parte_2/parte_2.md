# Parte 2

## Flujo colaborativo

1. Fork - Primero se hace el fork del repositorio original
2. Clone - Se clona el contenido del fork en el entorno de programación
3. Branch - Se crea la rama en la que se trabajará
4. Modificar archivos - Se modifican los archivos que se necesiten
5. Add - Se da un git add para guardar todos los cambios
6. Commit - Se crea una nueva versión del programa
7. Push - Se hace un git push desde la rama creada para mandar la información al repositorio fork
8. Pull Request - Desde el repositorio se da un pull request para que el propietario original lo acepte o no
9. Merge - En caso de aceptar los cambios, estos se fusionan con el proyecto original
10. Review - Se verifican los cambios realizados

## Fork y Clone

Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”.

    Respuesta: Es incorrecta, Clone crea una copia del proyecto dentro del entorno de desarrollo local (VSC o cualquier otro), no desde la nube o alguna cuenta.

## Pull Request

Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. ¿Los cambios ya forman parte del repositorio original? ¿Qué debe ocurrir para incorporarlos?

    Respuesta: Para que los cambios se puedan visualizar en el repositorio original se debe de realizar un push request que el propietario del proyecto puede aceptar o rechazar.

## Request Changes

El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear otro Pull Request y qué ocurre cuando realizas nuevamente push.

    Respuesta: Si se modifican la rama de un proyecto al que se le solicitó ya un pull request y se hace un push, estos nuevos cambios se actualizan desde el repositorio y el propio pull request, apareciendo para verificarse.

## Merge y repositorio local

Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

    Respuesta: No se visualizan porque el repositorio local y en la nube no se encuentran sincronizados en tiempo real. Se debe de hacer un pull desde el local para cargar todos los datos modificados.

## Synk Fork

Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.

    Respuesta: Los comandos de git como pull o clone serían las herramientas a utilizar para cargar los cambios al repositorio local.

    Synk Fork es una función de GitHub que sube a la nube los diferentes commits realizados automáticamente sin necesidad de personalmente hacer un push cada vez, mientras que el git pull es el comando con el que la información modificada del repositorio en la nube se sube al local.