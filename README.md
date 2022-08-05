## Descripción

El contenedor es un servidor apache el cual cuenta con una pagina web expuesta en el puerto 8080:

Al terminar la ejecución se podra observar la pagina web.

## Compilación del contenedor

    docker build -t dockerfile:tarea_apache .

## Ejecución del contenedor

   docker run -dit --name test -p 8080:80 dockerfile

