# Tarea 4

## Dockeriza el proyecto Newspaper utilizando Docker compose

Dockeriza el proyecto Newspaper para 2 ambientes de trabajo (desarrollo y producción) con los siguientes detalles:
- Para el ambiente de desarrollo debe crear un Dockerfile.dev y docker-compose.dev.yml con dos servicios configurados: 1. php-fpm y 2. postgresql
- Para el ambiente de produción debe crear un Dockerfile y
docker-compose.yml con dos servicios configurados: 1. nginx con php-fpm y 2. postgresql.

Puede utilizar el ejemplo del rama (docker) del repositorio (https://github.com/univalle-postgrado/lumen8-api-restful-newspaper/tree/docker). En este ejemplo existen 2 ambientes de trabajo (dev y prod), revisa el README del proyecto para más detalles.

Una vez realizado y probado debe enviar todo el proyecto más su colección de Postman y documentar las pruebas realizadas con capturas de pantalla en un documento PDF. Todo esto debe comprimirse en un archivo zip con el formato: nombres_apellidos_practica4.zip.
