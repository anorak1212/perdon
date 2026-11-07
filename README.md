# Perdón

Tarjeta web interactiva de una sola página: se abre un sobre, aparece el muñeco de nieve en 3D y después la carta.

## Contenido

- `index.html` — toda la aplicación (HTML, CSS y JS en un solo archivo).
- `favicon.ico` — icono multi tamaño (16, 32, 48, 64, 128, 256 px).
- `icon-128.png`, `icon-256.png`, `icon-512.png` — iconos PNG para navegador, PWA y vista previa al compartir.
- `apple-touch-icon.png` — icono para "agregar a pantalla de inicio" en iOS.
- `site.webmanifest` — manifiesto de la aplicación web.
- `subwoofer-lullaby.mp3` — música de fondo en bucle (8.3 MB, 3:28, 320 kbps), al 20 % de volumen.

## Dependencias externas

Se cargan por CDN, no hay que instalarlas:

- Three.js r128 (CDNJS) para el muñeco 3D.
- Google Fonts: Press Start 2P y VT323.

## Uso local

Abre `index.html` con doble clic. No requiere servidor ni compilación.

Los navegadores bloquean el audio automático: el mp3 arranca con el primer toque, clic o tecla. El botón de la esquina superior derecha silencia y reanuda sin perder la posición.

## Publicación

Servido con GitHub Pages desde la rama `main`, carpeta raíz:
https://anorak1212.github.io/perdon/

## Notas

- El icono se generó a partir de `images (1).png` (554 x 554 px), reescalado a los tamaños necesarios.
- La música es `Subwoofer Lullaby` (C418). Es material con derechos de autor: el repositorio es público, así que se usa solo para compartir el enlace de forma privada. Si el enlace se va a difundir, conviene sustituirla por un tema libre.
