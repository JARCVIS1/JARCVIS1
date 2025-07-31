Proyecto de Carrito Autónomo - Equipo JARCVIS

🚀 Bienvenidos al repositorio de Futuros Ingenieros - WRO 2025
Este espacio pertenece al equipo Futuros Ingenieros, conformado por las estudiantes Yuleimy Ramos y Susan Montero, bajo la guía de su profesora asesora Suely Contreras. Aquí compartimos el desarrollo de nuestro proyecto para la World Robot Olympiad, desde la idea inicial hasta las soluciones implementadas en hardware y software.

Nuestro objetivo es aplicar el conocimiento en robótica, programación y diseño para resolver retos reales de forma creativa y funcional. Cada archivo, línea de código y diseño refleja nuestro compromiso con el aprendizaje, la innovación y el trabajo en equipo.

Por Qué Decidimos Participar en Esta Competencia
Decidimos participar en esta competencia por varias razones clave:
1.	Desarrollo de Habilidades Técnicas: La competencia nos brinda la oportunidad de aplicar y mejorar nuestras habilidades en programación, electrónica, y diseño mecánico. Trabajar en un proyecto práctico nos permite poner en práctica lo aprendido en el aula y adquirir nuevas habilidades en el proceso.
2.	Innovación y Creatividad: Nos apasiona la innovación y esta competencia nos desafía a pensar creativamente para resolver problemas complejos. Desarrollar un carrito autónomo que pueda navegar por una pista con obstáculos requiere de soluciones ingeniosas y creativas.
3.	Trabajo en Equipo: Participar en la competencia nos permite fortalecer nuestras habilidades de trabajo en equipo. Colaborar estrechamente para alcanzar un objetivo común nos enseña la importancia de la comunicación, la cooperación y la gestión del tiempo.
4.	Diversión y Pasión por la Robótica: Nos apasiona la robótica y nos divierte construir y programar robots. Participar en esta competencia nos permite hacer lo que nos gusta mientras nos desafiamos a nosotros mismos para alcanzar nuevas metas.
5.	Contribución al Conocimiento: Queremos contribuir al avance del conocimiento en el campo de la robótica. Al compartir nuestros resultados y aprendizajes, esperamos inspirar a otros estudiantes y entusiastas de la robótica.

Desafíos
Desafío Abierto
El carrito debe completar tres (3) vueltas alrededor de la pista.
Desafío de Obstáculos
El carrito debe completar tres (3) vueltas alrededor de la pista con señales de tráfico verdes y rojas colocadas aleatoriamente.
Señal Roja: Indica que el carrito debe mantenerse en el lado derecho del carril.
Señal Verde: Indica que el carrito debe mantenerse en el lado izquierdo del carril.
Al final de la segunda vuelta, la señal de tráfico final determina la dirección de la tercera vuelta:
Señal Verde: Continuar la tercera vuelta en la misma dirección.
Señal Roja: Dar la vuelta y completar la tercera vuelta en la dirección opuesta.
El carrito no debe mover ninguna señal de tráfico.
Después de completar las tres vueltas, el carrito debe encontrar un lugar de estacionamiento y realizar un estacionamiento en paralelo.

Lista de Materiales
Componentes Electrónicos
•	Placa de Arduino
•	Driver L293D
Componentes de Estructura y Montaje
•	Black steering wheel x 2
•	Transmission link x2
•	Hexagon adapter x 2
•	M4 locknut x 2
•	Latches M2 * 10 x 2
•	Bearing(12mm) x 2
•	Bearing (8mm)x 2
•	Cross sleeve x1
•	S3003 servo x 1
•	Servo Kit x 1
•	M2.5 * 8 screws x8
•	M3 * 22 Double pass copper column x4
•	M3 * 5 Flat head screw x2
•	Flange bearing disabilities x2
•	17MM coupling D-5MM x2
•	Gear x2
•	Rear wheel link x1
•	25MM metal gear motor x1
•	Motor mounting bracket x1
•	M3 * 12 Double pass copper column x4
•	M3 * 18 Double pass copper column x4
•	M3 * 35 single-pass copper column x4
•	M3 * 6 nylon screw + M3 nut + nylon column x5
•	Switch x1
•	Tie x10
•	Motor connection cable x3
•	Acrylic Chassis x 1
•	Anti-collision cotton x1
•	M3 * 8 screws x30
•	M3 * 10 screws x16
•	Nut M3 x20
•	65MM wheels x4
Esta lista de materiales incluye todos los componentes necesarios para ensamblar y poner en funcionamiento el carrito autónomo desarrollado por el equipo JARCVIS.

Instrucciones de Configuración
Montaje del Hardware
1.	Ensamble el chasis y coloque las ruedas.
2.	Monte los motores en el chasis y conéctelos a los drivers de motor.
3.	Conectar el sensor y el servo al driver.

Software
Lenguaje de programación: C
Entorno de desarrollo: Arduino IDE
Librerías:
•	NewPing (para sensores ultrasónicos)
•	#include<Servo.h>// Incluye la librería para controlar el servo
•	#include<AFMotor.h>// Incluye la librería para controlar el motor L293D

Mejoras Futuras
Técnicas avanzadas de estacionamiento en paralelo
Mejora del código de evasión de obstáculos y planificación de rutas

¡Gracias por acompañarnos en este viaje hacia el futuro de la ingeniería!

>[!NOTE]
>Aqui puedes encontrar los link:
Prueba del Desafío Abierto: Demostración del carrito completando tres vueltas en la pista con ubicaciones aleatorias de las paredes internas.



