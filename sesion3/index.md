---
layout: default
title: Almacenamiento y Redes
nav_order: 4
has_children: true
---
# Almacenamiento y redes en Docker

## Almacenamiento

**Los contenedores son efímeros**, es decir, los ficheros, datos y configuraciones que creamos en los contenedores sobreviven a las paradas de los mismos pero, sin embargo, son destruidos si el contenedor es destruido. 

Ante la situación anteriormente descrita Docker nos proporciona varias soluciones para persistir los datos de los contenedores:

* Los **volumenes docker**.
* Los **bind mount**

## Redes 

Aunque hasta ahora no lo hemos tenido en cuenta, cada vez que creamos un contenedor, esté se conecta a una red virtual y docker hace una configuración del sistema (usando interfaces puente e iptables) para que la máquina tenga una ip interna, tenga acceso al exterior, podamos mapear (DNAT) puertos,...)

Cuando instalamos docker tenemos las siguientes redes predefinidas:

* Red de tipo bridge
* Red de tipo host
* Red de  tipo none


-----
* Ejemplo almacenamiento: mariadb (quizás no, porque vamos a ver ejemplo 3 wordpress + mariadb)
* Tipos de redes en docker (con parte de Introducción a las redes)
* Redes definidas por el usuario (Gestionando las redes en docker y Uso de las redes bridge definidas por el usuario)
* Ejemplo 1
* Ejemplo 2
* Ejemplo 3


