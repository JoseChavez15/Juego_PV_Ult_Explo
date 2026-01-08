RoboBlast: Demo Shooter en Tercera Persona (Godot 4, 3D)

Esta demo open-source para Godot 4 muestra cómo crear un controlador de personaje 3D inspirado en juegos como Ratchet and Clank o Jak and Daxter.
Puedes copiar el personaje directamente a tu proyecto como un asset plug-and-play para prototipar juegos 3D y ampliarlo según tus necesidades.

Incluye un personaje que puede correr, saltar, atacar cuerpo a cuerpo, apuntar, disparar y lanzar granadas.

Hay dos tipos de enemigos:

Avispas voladoras que disparan proyectiles.

Escarabajos que atacan por tierra.

El entorno incluye cajas rompibles, plataformas de salto y monedas que se mueven hacia el personaje del jugador.

Cómo ejecutar el proyecto

Descarga o clona el repositorio de GitHub.

Presiona <kbd>F5</kbd> o selecciona Run Project.

Controles

<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> o <kbd>stick izquierdo</kbd>: moverse.

<kbd>Mouse</kbd> o <kbd>stick derecho</kbd>: mover la cámara.


Preguntas Frecuentes (FAQ)
¿Cómo uso el personaje del jugador en mi juego?

Copia las siguientes carpetas en la raíz de tu proyecto:

Player: contiene los assets y escenas principales del jugador.

shared: contiene los shaders utilizados por el jugador.

Las siguientes acciones deben existir en el Input Map para que Player.tscn funcione correctamente:

move_left, move_right, move_up, move_down: mueven al personaje según la orientación de la cámara.

camera_right, camera_left, camera_up, camera_down: rotan la cámara alrededor del personaje.

jump, attack, aim, swap_weapons: botones de acción del personaje.
