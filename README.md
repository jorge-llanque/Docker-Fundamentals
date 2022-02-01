# Docker-Fundamentals
- Para ver los servicios corriendo
    - docker ps
- Para crear un nuevo contenedor
    - docker run -d -p 80:80 apache
- Para eliminar un contenedor porque vamos a usar el mismo puerto
    - docker rm -fv <namedelContenedor>
- Para construir una imagen 
    - docker build -t <nombreimagen> .
- Para ver los logs del container que está corriendo
    - docker logs -f <nombredelContenedor>


# Dockerfile
- Sirve para crear imagenes y procesos de despligue con el editor de consola vim