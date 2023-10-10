# Jose Carlos - Dispositivos y cableado
# Johan - Estudio del Arduino Mega 2560
## ***Estudio del Arduino mega 2560***


Arduino Mega 2560 es una tarjeta de desarrollo de Hardware libre construida con el microcontrolador Atmega 2560, que le da sentido a su nombre. Forma parte del proyecto Arduino que involucra una comunidad internacional dedicada al diseño y manufactura de placas de desarrollo de Hardware.
<![endif]-->

## ***Características***

Microcontrolador: ATmega2560

Voltaje Operativo: 5V

Tensión de Entrada: 7-12V

Voltaje de Entrada(límites): 6-20V

Pines digitales de Entrada/Salida: 54 (de los cuales 14 proveen salida PWM)

Pines análogos de entrada: 16


## ***Velocidad microcontrolador***

En cuanto a la velocidad del microcontrolador podemos decir que cuenta con un Cristal de 16MHz y una memoria Flash de 256K. Maneja un rango de voltaje de entrada de entre 7 y 12 volt, se recomienda una tension de entrada planchada en 9 Volt.

## ***Alimentación del Arduino mega 2560***

La placa Arduino mega 2560 puede alimentarse a través de la conexión USB o con una fuente de alimentación externa. La placa selecciona a la fuente de poder automáticamente.

La alimentación externa (no por USB) puede provenir de un adaptador de CA-CC o de una batería.

## ***Microcontrolador Atmel Amega2560***

El **microcontrolador Atmel Atmega2560-16AU** está fabricado con **tecnología CMOS** de 8 bits y baja potencia, basado en la **arquitectura RISC** mejorada de AVR.
<![endif]-->

## ***PWM***

El **Arduino Mega 2560** tiene 54 pines de entrada/salida, de los cuales exactamente 14 de ellos pueden ser utilizados como salidas de [PWM (Modulación por ancho de pulso), cuenta con otras 16 entradas analógicas y 4 UARTs (puertos serial).


## ***¿Cómo es la comunicación entre el Arduino y el ordenador?***

La comunicación entre la tarjeta **Arduino**  y la computadora se establece a traves del puerto serie, cuenta con un convertidor interno USB - SERIE de manera que no es necesario agregar ningún dispositivo externo para programar el microcontrolador.

## ***Ventajas***

Es una placa de desarrollo robusta de la familia, cuenta con un microcontrolador muy potente de 8 bits y es el que mas pines tiene de todas las opciones posibles.

Tiene una memoria destinada a la programación elevada.

## ***Memoria del Arduino mega 2560***

La placa Arduino mega 2560 tiene una capacidad 256 KB de memoria **FLASH** para almacenar el código de programa de los sketches, de los cuales 8 KB se utilizan para el gestor de arranque, 8 KB de **SRAM** y 4 KB de **EEPROM**.

## ***Entradas y salidas del Arduino mega 2560***

Cada uno de los 54 pines digitales de la placa Arduino mega 2560 se puede usar como entrada o salida, usando las funciones **pinMode**, **digitalWrite** y **digitalRead**.



https://github.com/Escuela-de-Ingenierias-Industriales/RegulacionAutomatica-ra2023grupo05/assets/145485196/83f7b510-8728-4b41-b0c2-8789275d2f61



# Adrián - Estudio de la programación en Simulink del Arduino Mega 2560
## ***1) INSTALACIÓN***

Adds ons > Get Hardware support packages > Arduino > Simulink > setup >
test conection
SIN MODO ADMINISTRADOR ; No instalar drivers > verifcar administrador dispositivo windows > Serial > Arduino Mega 2560

## ***2) CONFIGURAR MODELO***

Model configuration parameters > Hardware Implementation >Hardware board > Arduino Mega 2560
SI NO RECONOCE ARDUINO; Hacemos los mismos pasos y además “target > Host connections > manually > com x”

## ***3) MODOS DE EJECUCIÓN***

Simulación solo Pc
Hardware
-IO connected --> I/S target
- External <-- ej.target
- Deploy -->Target + arduino

## ***4) BLOQUES QUE USAREMOS***

- Digital input
- Digital output
- Analog input --> CAD 106
- PWM
- Scope
- Display

https://github.com/Escuela-de-Ingenierias-Industriales/RegulacionAutomatica-ra2023grupo05/assets/145486042/dce2ecac-2bde-405b-b0b2-9b6344aa70de


  
