---
layout: home
title: Inicio
nav_order: 1
---

# Introducción a Docker
{: .fs-9 }

Desarrollado para el CPR de Badajoz (Abril 2022).
{: .fs-6 .fw-300 }

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