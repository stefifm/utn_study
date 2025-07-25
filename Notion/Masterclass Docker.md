Docker permite reducir el tiempo de mostrar un simple hola mundo. Me olvido del SO, del entorno y del lenguaje.

Sin Docker: Configuración manual, horas de capacitación, Resultados variables y Difícil de replicar

Con Docker: configuración automática, minutos para empezar, resultados consistentes, fácil de replicar.

Beneficios: inicio inmediato, portabilidad, resultados consistentes, escalabilidad sencilla, actualizaciones fáciles

Aplicaciones reales: nuevas sucursales, eventos de catering, capacitación, franquicias

Docker se puede trasladar, garantiza consistencia, acelera el crecimiento y simplifica

Problemas en el proceso del software: construir, distribuir y ejecutar. Con docker podemos hacerlo en cualquier lado

Los contenedores

- Flexible
- Liviano
- Portables
- Bajo acoplamiento
- Escalables
- Seguros

  

Las aplicaciones no son solo código, también tienen dependencias: NodeJS, NPM, paquetes de SO, code. Todo lo podemos transformar en un artefacto

Para hacer el dockerfile, es importante saber el ciclo de vida de la aplicación.

Container run: registro (repositorio de imágenes docker hub) → imagen → docker run / podman run / rkt run / finch run / ctr container create / kubectl run → contenedor

Buenas prácticas: descomponer para agilidad, automatizar todo, herramientas estandarizadas, seguridad, infraestructura como código

  

## Docker

Permite desplegar aplicaciones en contenedores, de forma rápida y portable

Tips: Golang el nuevo java

Ejemplo de código

```Docker
docker run —name web -d -p 80:80 nginx:alpine
```

Para hacer el `docker build` debe existir un dockerfile

Los contenedores son efímeros, para la persistencia se debe recurrir a los volúmenes.

Docker compose permite orquestar múltiples contenedores.

Tips: usar imágenes oficiales

docker ps para listar contenedores

docker ps -a para listar todos los contenedores activos y no activos

docker rm id_contenedor o nombre_contenedor para eliminar un contenedor

docker run nginx para correr o comenzar un contenedor

- Si se pone nginx pelado, descargará la última versión. Mejor: usar las versiones para evitar actualizaciones indeseadas.

docker stop para detener un contenedor

docker rmi para borra imágenes

docker pull para descargar la imagen

Para ejecutar un comando dentro del contenedor: docker exec distracted_mcclintock cat /etc/hosts

docker run .d para levantar un contendor

Para usar versiones: docker run redis:4.0

Puertos

- con docker run va a estar de forma interna
- Para acceder, usar -p. 80:5000 donde 80 es donde vamos a acceder y 5000 es el puerto del contenedor
- Con base de datos no se habilita los puertos salvo que tengamos que conectarnos a través de una herramienta: dbvear, data grip, workbench

Volumenes

- Indicar un espacio de memoria para que persistan los datos en el contenedor
- Ejemplos de persistencia: base de datos
- `docker run -v /opt/datadir:/var/lib/mysql mysql`
- Dos tipos: lectura/escritura (wordpress) y sólo lectura (base de datos)
- Docker y bind mount
    
    - tmpfs volumen de memoria
    - volumen: aria de docker
    - bind mount comparte una área de mi máquina física
    - Comandos
    
      
    

Para inspeccionar contenedores: docker inspect nombre_contenedor

Variables de entorno: -e o —env

```Docker
docker run -it —name prueba -e USUARIO=prueba ubuntu bash
```

Redes

- Cada contenedor tiene su capa de red
- Se pueden genera puentes dentro de los contendores para poder verlos
- Tipo bridge, host y none.
- docker network create
- docker network ls
- docker network create rm/prune

Dockerfile

FROM imagen base

RUN actualizar repositorio en caso de SO

RUN para instalar cosas en tiempo de construcción

COPY copiar código fuente

ENTRYPOINT ejecutar en el servidor

docker build Dockerfile -t nombre_contenedor

docker push nombre_contenedor

Tips

- FROM
- LABEL: metadata
- Instrucciones de construcción: RUN, COPY, ADD, WORKDIR
- Configuración: variables de entornos, usuarios, puertos: USER, EXPOSE, ENV
- Instrucciones de arranque: CMD (ejecuta el comando directamente), ENTRYPOINT (genera scripts)
- En windows, los volúmenes están en \\wsl.localhost\docker-desktop-data\data\docker\volumes
- Hadolint: un linter completo

docker login: para loguearse en Docker hub

docker tag para tagear nuestra imagen

Ciclo de vida

- Desarrollo de la app
- Crear la imagen del docker
- Probar la app
- Distribuir la imagen
- Implantación de la app en entorno de producción

Docker compose

- herramienta versátil que permite definir y gestionar aplicaciones multi-contenedor de forma sencilla.
- Es una forma de orquestar
- No se recomienda para llevarlo a producción.
- Es solo para probar