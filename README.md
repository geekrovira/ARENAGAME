# Arena Shooter 3D

Juego de disparos en primera persona (FPS) en 3D que corre en el navegador.
Te enfrentas a un bot controlado por la computadora dentro de una arena cerrada.
Gana el primero que consiga 5 bajas.

[JUEGO](https://geekrovira.github.io/ARENAGAME/)

## Cómo jugar

Abre `index.html` en cualquier navegador moderno (Chrome, Edge, Firefox).
Necesita conexión a internet la primera vez para descargar la librería Three.js desde un CDN.

| Tecla | Acción |
|-------|--------|
| ↑ / ↓ | Avanzar / retroceder |
| ← / → | Girar a la izquierda / derecha |
| Espacio | Disparar |
| P o Esc | Pausar |
| Enter | Comenzar / reiniciar |

También funcionan W, A, S, D como alternativa (A y D se desplazan de lado).

## Características

- Arena 3D con muros, pilares, cajas y sombras en tiempo real.
- Bot enemigo con inteligencia artificial: patrulla, te persigue cuando te ve,
  se mueve de lado mientras dispara, rodea obstáculos y busca botiquines cuando está herido.
- Tres niveles de dificultad (Fácil, Normal, Difícil).
- HUD con barra de vida, marcador, cronómetro, vida del bot y minimapa.
- Botiquines que restauran 40 puntos de vida y reaparecen a los 20 segundos.
- Efectos de sonido sintetizados con Web Audio (sin archivos externos).

## Servir en local (opcional)

Si prefieres servirlo por HTTP:

```bash
python -m http.server 8000
```

y abre http://localhost:8000 en el navegador.
