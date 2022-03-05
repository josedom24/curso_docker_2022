---
layout: home
title: Inicio
nav_order: 1
---

# Introducción a Docker
{: .fs-9 }

Desarrollado para el CPR de Badajoz (Abril 2022).
{: .fs-6 .fw-300 }

## Justificación

En los últimos años se ha ido extendiendo el uso de contenedores como elementos esenciales para el uso de aplicaciones en entornos en producción, tanto más cuanto más variable sea la demanda, la frecuencia con la que se actualizan o la necesidad de que funcionen de forma ininterrumpida.

Gestionar una aplicación sobre contenedores, que pueda actualizarse rápidamente, que sea escalable o tolerante a fallos, es una tarea compleja que se realiza mediante un software específico. 

Docker es una empresa (Docker Inc.) que desarrolla un software con el mismo nombre, de forma más concreta el software denominado (docker engine), que ha supuesto una revolución en el desarrollo de software, muy ligado al uso de contenedores de aplicaciones, a las aplicaciones web y al desarrollo ágil.

Docker permite gestionar contenedores a alto nivel, proporcionando todas las capas y funcionalidad adicional y, lo más importante de todo, es que proporciona un nuevo paradigma en la forma de distribuir las aplicaciones, ya que se crean imágenes en contenedores que se distribuyen, de manera que el contenedor que se ha desarrollado es idéntico al que se utiliza en producción y deja de instalarse la aplicación de forma tradicional.

En este curso se va introducir el concepto de la puesta en producción de aplicaciones web usando contenedores Docker.

## Objetivos

* Conocer las ventajas que nos proporciona el uso de la tecnología de contenedores.
* Conocer los conceptos principales sobre el despliegue de aplicaciones web utilizando contenedores.
* Conocer los conceptos fundamentales sobre docker.
* Trabajar con imágenes docker.
* Desplegar aplicaciones web sencillas en contenedores.
* Introducción al uso del almacenamiento en docker.
* Introducción al uso de la redes en docker.
* Ser capaz de usar contenedores de terceros y de construir mis propios contenedores.    
* Creación de imágenes docker.
* Desplegar escenarios multicontenedor usando docker-compose.
* Estudiar el ciclo de vida del desarrollo, pruebas y despliegue de aplicaciones utilizando contenedores.

## Contenidos

Sesión 1: Introducción a los contenedores docker

* Instalación de docker
* El "Hola Mundo" de docker
* Ejecución simple de contenedores
* Ejecutando un contenedor interactivo
* Creando un contenedor demonio
* Creando un contenedor con un servidor web
* Configuración de contenedores con variables de entorno

Sesión 2: Imágenes Docker

* Registros de imágenes: Docker Hub
* Gestión de imágenes
* ¿Cómo se organizan las imágenes?
* Creación de contenedores desde imágenes
* Ejemplo: Desplegando la aplicación mediawiki 

Sesión 3: Almacenamiento y Redes en docker

* Los contenedores son efímeros
* Volúmenes docker y bind mount
* Asociando almacenamiento a los contenedores: volúmenes docker
* Asociando almacenamiento a los contenedores: bind mount
* Ejemplo 1: Contenedor nextcloud con almacenamiento persistente
* Ejemplo 2: Contenedor mariadb con almacenamiento persistente 
* Introducción a las redes en docker
* Tipos de redes en docker
* Gestionando las redes en docker
* Uso de las redes bridge definidas por el usuario
* Ejemplo 1: Despliegue de la aplicación Guestbook
* Ejemplo 2: Despliegue de la aplicación Temperaturas
* Ejemplo 3: Despliegue de Wordpress + mariadb
* Ejemplo 4: Despliegue de tomcat + nginx ????

Sesión 4: Creando escenarios multicontenedor con docker-compose 

* Instalación de docker-compose
* El fichero docker-compose.yml
* El comando docker-compose
* Almacenamiento con docker-compose
* Redes con docker-compose
* Ejemplo 1: Despliegue de la aplicación guestbook
* Ejemplo 2: Despliegue de la aplicación Temperaturas
* Ejemplo 3: Despliegue de WordPress + Mariadb
* Ejemplo 4: Despliegue de tomcat + nginx 

Sesión 5: Creación de imágenes en Docker 

* Creación de imágenes a partir de un contenedor
* Creación de imágenes a partir de un Dockerfile
* Distribución de imágenes
* Ejemplo 1: Construcción de imágenes con una página estática
* Ejemplo 2: Construcción de imágenes con una una aplicación PHP
* Ejemplo 3: Construcción de imágenes con una una aplicación Python
* Ciclo de vida de las aplicaciones 

## Metodología

El curso está pensado como una secuencia de complejidad creciente, en la que se irán introduciendo los diferentes elementos de Docker, hasta llegar a poder gestionar completamente el ciclo de vida de una aplicación en un entorno en producción.

En el curso se introducirán los conceptos más fundamentales de esta tecnología y se realizaran ejercicios prácticos de todos los elementos estudiados.

En la sesión inicial se hará una presentación un poco más teórica de los conceptos de contenedores y de la tecnología ofrecida por Docker, para  a continuación ir estudiando todos los contenidos del curso por medio de la realización de actividades y ejercicios.

Los materiales ofrecidos en el curso serna:

* Una página web con todos los contenidos que vamos a estudiar.
* Cinco videoconferencias donde se desarrollaran los distintos contenidos estudiados.

