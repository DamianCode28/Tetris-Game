🧱 Juego de Tetris
📌 Descripción del Proyecto

Este proyecto consiste en una implementación del clásico juego Tetris, desarrollada completamente con HTML, CSS y JavaScript puro, sin el uso de librerías o frameworks externos.
El objetivo del proyecto es recrear la mecánica original del juego, aplicando conceptos fundamentales de lógica de programación, manejo de eventos, temporizadores y manipulación del DOM.

El juego se ejecuta directamente en el navegador y ofrece una experiencia interactiva y fluida para el usuario.

🚀 Funcionalidades
🧩 Generación aleatoria de piezas (tetrominós)
⬅️➡️ Movimiento lateral de las piezas
⬇️ Caída automática de las piezas
🔄 Rotación de piezas
🧱 Detección de colisiones con bordes y piezas fijas
🧹 Eliminación de líneas completas
🎮 Controles por teclado

🛠️ Tecnologías Utilizadas

HTML5
Define la estructura del juego:

Contenedor del tablero

Panel de puntaje

Indicaciones de controles

CSS3
Encargado del diseño visual:

Estilizado del tablero y las piezas

Colores y animaciones

Diseño responsive

Organización del layout

JavaScript (ES6)
Lógica principal del juego:

Representación del tablero mediante arrays

Gestión de tetrominós y sus rotaciones

Control del tiempo con setInterval

Detección de colisiones

Eliminación de filas y actualización del puntaje

Captura de eventos del teclado

🧠 Funcionamiento del Juego

Al iniciar el juego, se genera un tetrominó de forma aleatoria.
La pieza comienza a descender automáticamente en intervalos de tiempo.
El jugador puede mover o rotar la pieza usando el teclado.
Cuando la pieza colisiona con el fondo o con otras piezas:
Se fija en el tablero.
Se genera una nueva pieza.
Al completarse una línea horizontal:
La línea se elimina.
Las piezas superiores descienden.
Se actualiza el puntaje.

El juego finaliza cuando las piezas alcanzan la parte superior del tablero.
