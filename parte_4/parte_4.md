# Parte 4

1. Explica la diferencia entre Git y GitHub.

    Respuesta: Git es una herramienta o serie de códigos que permiten a un repositorio local crear y controlar las versiones de un proyecto. GitHub es el repositorio en la nube en donde se puede almacenar un proyecto, así como trabajar con otras personas de forma sencilla.

2. Explica para qué sirve .gitignore.

    Respuesta: Es un archivo que indica a Git qué archivos no se subiran a GitHub.

3. Explica por qué .venv no debe almacenarse normalmente en GitHub.

    Respuesta: Porque al venv ser quien almacena cada versión del proyecto, si este se subiera al repositorio el peso del mismo aumentaría significativamente, además de ser redundante en ocasiones.

4. Explica para qué sirve requirements.txt.

    Respuesta: Muestra las bibliotecas instaladas en el proyecto así como sus versiones.

5. Explica la diferencia entre Stage, Commit y Push.

    Respuesta: Stage prepara los archivos para la futura creación de una versión. Commit crea las diferentes versiones completas del proyecto. Push sube la versión deseada a GitHub.

6. Explica por qué un repositorio puede tener varios commits antes de realizar un push.

    Respuesta: Porque el push manda únicamente la o las versiones deseadas a GitHub, y previo a eso, se pueden crear tantas como se quiera sin esto alterar el resultado final.