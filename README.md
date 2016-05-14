---
title:  "Beacon"
subtitle: "Envio de mensajes por medio de Beacon"
author: "Ivan Yam, Hector Polanco"
avatar: "img/authors/wferr.png"
image: "img/pannic_button/Logo.png"
date:   2015-05-12 12:12:12
---
#Beaconmatic’s#


##Definición del proyecto.
  Beaconmatic’s es un proyecto basado en el uso de Beacons para publicidad de establecimientos comerciales.

##¿Que es un beacon? 
  Un beacon es un dispositivo de bajo consumo que emite una señal broadcast, y son suficientemente pequeños para fijarse en una pared o mostradores utiliza conexión bluetooth de bajo consumo (BLE)  para transmitir mensajes o avisos directamente a un dispositivo móvil sin necesidad de una sincronización de los aparatos.

##¿Por qué Transmitir  una URL ?

  La transmicion de una URL nos brinda grandes beneficios:

  * Una página web con un enfoque a las necesidades del establecimiento
  * Solo requiere un navegador y no de aplicación por cada beacon.

##¿Por qué usar beacons?

  El número de objetos inteligentes va a explotar, tanto en nuestros hogares y en los espacios públicos. Al igual que la web, no va a ser una larga cola de interactividad para los objetos inteligentes. Sin embargo, la sobrecarga de la instalación de una aplicación para cada uno de ellos simplemente no escala. Necesitamos un sistema que le permite caminar y utilizar un dispositivo con sólo un toque. La Web física no se trata de sustituir las aplicaciones nativas; Se trata de permitir la interacción de los momentos en los que las aplicaciones nativas simplemente no son prácticos.

##Compatibilidad
  
  Es necesario contar con una una Flora Adafruit V2 y el módulo Flora Bluefruit LE para el desarrollo del emisor de Beacons.
  Además de un teléfono android con Bluetooth 4.0, Indispensable que sea 4.0 ya que hasta esta versión admite Beacons.

##Como usarlo

####Paso 1
  Se enciende el la flora y modulo bluetooth para activar el beacon ambos son alimentados por una bateria de 3.3V
    <img class="image-center" src="img/Beacons/Flora.png"/>

####Paso 2
  Es necesario encernder el Bluetooth en el dispositivo para la comunicacion con la flora.
    <img class="image-left" src="img/Beacons/Blue.png"/>

####Paso 3   
  Se abre la aplicacion The Physical Web no es necesario mantenerla abierta puede dejar en segundo plano.
    <img class="image-center" src="img/Beacons/App.png"/>

####Paso 4
  Cuando el dispositivo pase cerca de un transmisor Beacon este recibira el mensaje al telefono.
    <img class="image-center" src="img/Beacons/Caja.png"/>
    
####Paso 5
  Cuando el telefono reciba el beacon se activara una notificacion, al pulsar sobre ella nos abrira la URL.
    <img class="image-center" src="img/Beacons/Notificacion.png"/>

## Listo!!!    
   

##Demostracion (Video Promocional)
  <img class="image-center" src="img/Beacons/Video.PNG"/>
  
[Ver Video](https://youtu.be/8h5rDCZnrlQ)

## Lenguajes de programación :
* Arduino: Usado para la configuracion de la Flora y el modulo Bluetooth. [Ver repositorio](https://github.com/IvanJYL/Beacons/tree/master/PhysicalWeb)
* Java: usado para el desarrollo de la aplicación móvil. [Ver repositorio](https://github.com/IvanJYL/Beacons/tree/master/PhysicalWeb)

## Detalles Tecnicos:
  Flora Adafruit V2  [Ver Elnace](http://adafru.it/659)
  
  Flora Bluefruit LE [Ver Elnace](http://adafru.it/2487)
  

### Equipo:
    Ivan De Jesus Yam Lino
    Hector Rodrigo Polanco Balam
