# 🦆 Duck Game

Mini juego desarrollado con JavaScript puro (Vanilla JS), HTML y CSS.  
El jugador controla un pato que puede moverse horizontalmente y esquivar obstáculos.

---

## 🎮 Características

- Movimiento horizontal controlado por teclado
- Sistema de niveles con aumento progresivo de dificultad
- Detección de colisiones
- Animaciones con CSS (salto y caída)
- Game loop usando `requestAnimationFrame`
- Control de límites de pantalla

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3 (animaciones, position, transform)
- JavaScript (DOM manipulation, game loop, lógica de movimiento)

---

## 🧠 Conceptos aplicados

Este proyecto fue desarrollado para reforzar conceptos fundamentales de frontend:

- Manejo de estado con variables (posición y velocidad)
- Manipulación dinámica del DOM
- Uso de `requestAnimationFrame` para animaciones fluidas
- Cálculo de límites usando `window.innerWidth`
- Sistema de niveles con configuración dinámica
- Detección básica de colisiones

---

## ⚙️ Cómo funciona el movimiento

La posición horizontal del pato se guarda en una variable (`duckX`).  
En cada frame:

1. Se actualiza la posición según la velocidad.
2. Se valida que no se salga de la pantalla.
3. Se renderiza la nueva posición en el DOM.

Esto sigue la estructura clásica de un game loop:

- Update (lógica)
- Render (visualización)

---

## 🚀 Cómo ejecutarlo

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/duck-game.git
