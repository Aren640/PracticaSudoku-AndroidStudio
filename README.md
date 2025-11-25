<p align="center"> <img src="/mnt/data/10b58eab-afa3-4953-8919-3787a7668f2f.png" width="200"> </p> <h1 align="center">🧩 SUDOKU – Proyecto Android Studio</h1> <p align="center"> Desarrollo de una práctica completa de un juego de Sudoku para Android. </p>
📑 Índice

📘 README – Practica Sudoku (Android Studio)

📝 Descripción general

🎨 Diseño inicial

🧩 Menú Principal

1️⃣ Nueva Partida

2️⃣ Puntuaciones

3️⃣ Salir

🎮 Controles del Juego

🏆 Ejemplo de Clasificación

📱 Capturas del diseño (Figma)

🛠 Tecnologías utilizadas

👨‍💻 Autor

📝 Descripción general

Este proyecto consiste en el desarrollo de un juego de Sudoku para Android, diseñado desde cero utilizando:

🎨 Maquetación en Figma

📱 Implementación en Android Studio

📄 Documentación completa en Notion + README

El objetivo es crear una aplicación funcional que permita:

✔ Crear partidas de diferentes dificultades
✔ Permitir al jugador interactuar con el tablero
✔ Guardar puntuaciones según tiempos
✔ Mostrar clasificaciones por nivel
✔ Controlar estados del jugador (errores, pistas, rendirse…)

🎨 Diseño inicial

Para comenzar el proyecto, se diseña un logo simple y atractivo acorde a la estética general del juego (blanco cálido + naranja).

<p align="center"> <img src="/mnt/data/10b58eab-afa3-4953-8919-3787a7668f2f.png" width="160"> </p>
🧩 Menú Principal

El menú principal contiene tres opciones básicas:

Opción	Descripción
Nueva Partida	Comienza una partida eligiendo dificultad
Puntuaciones	Consulta los mejores tiempos guardados
Salir	Cierra la aplicación
1️⃣ Nueva Partida
1.1 Dificultad
🟢 FÁCIL

Pistas disponibles

Muchos números rellenados desde el inicio

Marca errores en rojo

🟠 MEDIO

Algunos números puestos

Sin pistas

Errores no marcados

🔴 DIFÍCIL

Muy pocos números puestos

No muestra errores hasta el final

1.2 Insertar nombre

El jugador introduce un nombre que servirá para guardar su puntuación.

1.3 Jugar

Se genera un sudoku según dificultad

Se inicia el contador

El jugador juega hasta completar el tablero

Si no resuelve correctamente → no se guarda puntuación

Si lo resuelve correctamente → se guarda su tiempo

👉 Si ya existía una puntuación anterior y la nueva es mejor, se actualiza automáticamente.

🏆 Ejemplo de Clasificación
Clasificación Fácil (antes)

Martín → 2:20

Samuel → 2:30

Carlos → 3:00

Carlos termina en 2:05 → se actualiza.

Clasificación Fácil (después)

Carlos → 2:05

Martín → 2:10

Samuel → 2:30

2️⃣ Puntuaciones

Se divide por dificultades:

Fácil → lista de tiempos ordenados

Medio → lista de tiempos ordenados

Difícil → lista de tiempos ordenados

3️⃣ Salir

Regresa a la pantalla principal o cierra la aplicación completamente.

🎮 Controles del Juego

Durante la partida, el jugador puede:

Seleccionar una casilla vacía

Introducir números del 1 al 9

Borrar un número introducido

Deshacer el último movimiento

Ver un temporizador activo

Usar botón de pista (solo en Fácil)

Pulsar “Rendirse” para abandonar la partidado para tener una clave principal con la que poner y guardar sus resultados.

