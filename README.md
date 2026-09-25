# Arcade AEMATEC

Página web de minijuegos retro en español, en un solo archivo HTML (`index.html`).

## Juegos

- **Buscaminas**: tres niveles (fácil, medio y difícil).
- **Batalla Naval**: contra la CPU o en línea con un amigo.
- **Animal al Tiro**: consigue la mayor cantidad de puntos en 45 segundos.
- **Carreras**: en bicicleta, patineta o patines, con 3 circuitos, en modo local o en línea.
- **Combate de Funciones**: escribe `y = f(x)` y dispara su gráfica contra el equipo rival.

Cada juego tiene su tabla de posiciones TOP 10.

## Cómo usarlo

Abre `index.html` en un navegador. No hace falta instalar nada ni compilar.

Si Firebase no está disponible, la página funciona en modo local, sin tablas de posiciones compartidas ni partidas en línea.

## Firebase (partidas en línea y tablas de posiciones)

El proyecto usa Firebase (`arcade-matec`). En la consola de Firebase:

1. En **Authentication > Método de acceso**, activa el acceso **Anónimo**.
2. Crea la base de datos de **Firestore**.
3. Publica las reglas de seguridad de Firestore (`firestore.rules`).

## Créditos

Realizado por **Antony Arias**, 2026.
