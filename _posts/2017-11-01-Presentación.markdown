---
layout: post
title:  "Presentación"
date:   2017-11-01 00:00:00 +0100
categories: Presentacion
---
{:indented: style="text-indent: 30px; text-align: justify"}
Bienvenido a mi blog. En él voy a mostrar un sistema de control de casa con el que se puede gestionar desde la conexión/desconexión de la calefacción, hasta un sistema de riego automático para un huerto, en mi caso varios maceteros que he puesto en la terraza. También hay una cámara web que puede tomar fotografías cuando decidas.
{:indented}

{:indented: style="text-indent: 30px; text-align: justify"}
Es posible que no hayáis oído nunca hablar de estas cosas o quizás las conocéis de sobras. En cualquier caso lo que aquí vais a encontrar es parte por parte como se programa y se configura cada una de las partes.
{:indented}
{:indented: style="text-indent: 30px; text-align: justify"}
Todo el sistema se gestiona desde un mini ordenador (Raspberry PI)
{:indented}
{:center: style="text-align: center"}
[![/imagenes/Raspberry.jpg]({{ site.baseurl }}/imagenes/Raspberry.jpg "Raspberry PI")](https://www.raspberrypi.org/)
{:center}

que se encarga tanto de las tareas rutinarias (programación del riego) como de la comunicación con el exterior.

{:indented: style="text-indent: 30px; text-align: justify"}
Los controles de calefacción, bomba de riego, sensores de temperatura interior y exterior, humedad exterior y del macetero, nivel de agua del depósito y demás sistemas de control, se realizan con una placa Arduino.
{:indented}
{:center: style="text-align: center"}
[![/imagenes/Arduino.jpg]({{ site.baseurl }}/imagenes/Arduino.jpg "Arduino")](https://www.arduino.cc/)
{:center}


{:indented: style="text-indent: 30px; text-align: justify"}
No es necesario tener ninguna pantalla ni botonera (aunque sería muy fácil de configurar)  porque todo el sistema se supervisa desde un teléfono con S.O. Android que puede ver estados de todo el sistema, cambiar la configuración y recibir las imágenes captadas por la página web. Para ello tendremos que conectar la Rasberry PI a internet, bien por el puerto Ethernet o por WIFI.
{:indented}

{:indented: style="text-indent: 30px; text-align: justify"}
Los distintos elementos del sistema se conectan entre sí de manera que cuando se produce un evento, se informa del mismo, p.e. cuando se dispara el temporizador de riego, además de conectar la bomba (o el sistema que se desee), se envía un eMail a la cuenta configurada informando del inicio y fin de riego, nivel de humedad y nivel del depósito de agua.
{:indented}

{:indented: style="text-indent: 30px; text-align: justify"}
Si ya conocéis como funcionan estos aparatos, seguramente os podréis saltar alguno de los pasos que iré explicando,  a pesar de todo espero que os sea útil, si no habéis programado nunca hay algunos archivos que os serán muy útiles, ya que contienen las herramientas necesarias y suficientes para poder comunicar unos módulos con otros.
{:indented}

{:indented: style="text-indent: 30px; text-align: justify"}
Y esto es solo el principio, una vez que hayas seguido las instrucciones que encontrarás en este blog, podrás hacer muchas mas cosas.
{:indented}
{:indented: style="text-indent: 30px; text-align: justify"}
Espero que te resulte de utilidad todo lo que vas a ver en estas páginas.
{:indented}
{:indented: style="text-indent: 30px; text-align: justify"}
Un saludo...
{:indented}