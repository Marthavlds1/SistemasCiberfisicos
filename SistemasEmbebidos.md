
---
layout: default
title: Sistemas Embebidos
parent: "Prácticas"
nav_order: 1
---
# Sistemas Embebidos 
Los Sistemas Embebidos son sistemas que se componen por hadware y software, diseñadaspara realizar una o más funciones específicas (programadas por el usuario). optimizados para tareas dedicadas en lugar de ser computadoras de propósito general. Se caracterizan por estar integrados en un producto, incluyendo procesadores, memoria y entradas/salidas.

## Objetivo de la práctica
Familiarizarse con sistemas embebidos mediante la programación de diferentes microcontroladores para controlar sus LEDs integrados, entendiendo las diferencias entre arquitecturas AVR y ARM.
Ocupando los siguientes microcontroladores:
·Seeed Studio XIAO RP2040
·ESP32 (ESP32-WROOM-32 DevKit V1 y Seeed Studio XIAO ESP32S3 Sense)
·ATmega328P (Arduino Uno y Arduino Nano)

Durante esta práctica exploraremos:

·Arquitectura básica de cada plataforma y su "modelo mental": comprenderemos cómo funcionan la CPU, la memoria, los buses de comunicación y las entradas/salidas (I/O).
·Preparación del entorno de desarrollo: configuración de Arduino IDE y Thonny (MicroPython) para cada familia de microcontroladores.
·Programa "Blink": implementaremos el clásico programa de parpadeo de LED en cada tarjeta, utilizando tanto Arduino IDE como MicroPython cuando sea aplicable.

## Microcontroladores
### Arduino Uno (ATmega328P)