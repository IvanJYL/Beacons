---
title:  "Beacon"
subtitle: "Envio de mensajes por medio de Beacon"
author: "Ivan Yam, Hector Polanco"
avatar: "img/authors/wferr.png"
image: "img/pannic_button/Logo.png"
date:   2015-05-12 12:12:12
---
#Beacon#

Este es un proyecto experimental en etapa temprana en el que se busca llevar el Internet en las cosas.
Los Beacon es un esfuerzo para extender la superpotencia núcleo de la web, la URL, a los objetos físicos cotidianos. Nuestra premisa básica es que usted debería ser capaz de subir a cualquier objeto físico "inteligente " (por ejemplo, una máquina expendedora, un cartel, un juguete, una parada de autobús, un coche de alquiler) e interactuar con él sin necesidad de descargar una aplicación en primer lugar. La experiencia del usuario de los objetos inteligentes debe ser mucho como eslabones de un navegador web: es decir, basta con TOCAR y USAR. 

En su base, los Beacon es un servicio de localización: un objeto inteligente difunde URLs relevantes que cualquier dispositivo cercano puede recibir. Este simple capacidad puede abrir nuevas e interesantes formas de interactuar con la Web.

##¿Por qué URL ?

La URL que es el bloque de construcción fundamental de la web, brinda una extraordinaria flexibilidad de expresión. Puede ser:

* Una página web con sólo un pequeño párrafo de la información
* Una página web totalmente interactivo
* Un enlace profundamente en una aplicación nativa

##¿Por qué estamos haciendo esto?

El número de objetos inteligentes va a explotar, tanto en nuestros hogares y en los espacios públicos. Al igual que la web, no va a ser una larga cola de interactividad para los objetos inteligentes. Sin embargo, la sobrecarga de la instalación de una aplicación para cada uno de ellos simplemente no escala. Necesitamos un sistema que le permite caminar y utilizar un dispositivo con sólo un toque. La Web física no se trata de sustituir las aplicaciones nativas; Se trata de permitir la interacción de los momentos en los que las aplicaciones nativas simplemente no son prácticos.

###Como usarlo

#Paso 1
  Se enciende el la flora y modulo bluetooth para activar el beacon
    <img class="image-center" src="img/Beacons/Flora.png"/>

#Paso 2
  Es necesario encernder el Bluetooth en el dispositivo.
    <img class="image-center" src="img/Beacons/Blue.png/>
   
#Paso 3   
  Se abre la aplicacion The Physical Web y se deja en segundo plano.
    <img class="image-center" src="img/Beacons/App.png"/>

#Paso 4
  Cuando el dispositivo pase cerca de un Beacon este recibira el mensaje.
    <img class="image-center" src="img/Beacons/Caja.png"/>
    
#Paso 5
  Cuando el telefono reciba el beacon se activara una notificacion, al pulsar sobre ella nos abrira la URL.
    <img class="image-center" src="img/Beacons/Notificacion.png"/>

   ###Listo!!!    
   

##Demostracion
  <img class="image-center" src="img/Beacons/Video.png"/>
  
  [Ver Video](https://youtu.be/8h5rDCZnrlQ)

### Lenguajes de programación :
* Arduino: Usado para la configuracion de la Flora y el modulo Bluetooth. [Ver repositorio](https://github.com/IvanJYL/Beacons/tree/master/PhysicalWeb)
* Java: usado para el desarrollo de la aplicación móvil. [Ver repositorio](https://github.com/IvanJYL/Beacons/tree/master/PhysicalWeb)

### Equipo:
    Ivan De Jesus Yam Lino
    Hector Rodrigo Polanco Balam
