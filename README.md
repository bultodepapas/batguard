# BatGuard: presentación interactiva

**Sitio:** https://bultodepapas.github.io/batguard/

Presentación para defensa e inversores de BatGuard, una red acústica pasiva que detecta drones por su sonido y los ubica en un mapa 2D. Incluye simulaciones en vivo de la red, la firma acústica, la dirección de llegada, el despliegue de nodos y un nodo en 3D.

Todo el sitio está en `index.html`: HTML, CSS y JavaScript sin paso de compilación. Las tipografías vienen de Google Fonts y Three.js se carga desde cdnjs solo al acercarse al nodo 3D. Cada animación se pausa cuando sale de pantalla.

Las simulaciones corren en el navegador con geometría y ruido ilustrativos. No son resultados de campo.

## Mantenimiento

Este repositorio es una réplica publicada del directorio `presentacion/` del repositorio de desarrollo del proyecto, sincronizada con `git subtree`. Los cambios se hacen allí y se publican con `git subtree push`. Un commit hecho directamente aquí bloquea la siguiente publicación hasta integrarlo con `git subtree pull`.

GitHub Pages sirve la rama `main` desde la raíz; `.nojekyll` evita el procesamiento de Jekyll.
