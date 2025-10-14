# Casa Austin - Sistema de Cámaras

Sistema web para visualizar múltiples cámaras de seguridad en tiempo real.

## Características

- **15 cámaras simultáneas** con IDs del 101 al 1501
- **Streams MP4 directos** para mejor compatibilidad
- **Sistema de cola inteligente** (máximo 6 streams simultáneos)
- **Keep-alive automático** para mantener streams activos
- **Controles globales** (Play All, Pause All, Mute All, etc.)
- **Interfaz responsiva** que se adapta a diferentes tamaños de pantalla

## Uso

1. **Probar Conexión** - Verificar conectividad con el servidor
2. **Cargar Streams** - Cargar todos los streams de video
3. **Play All** - Reproducir todos los streams
4. **Keep Alive** - Reactivar streams si se pausan

## Tecnologías

- HTML5 Video
- JavaScript Vanilla
- CSS Grid
- Intersection Observer API

## URL de los Streams

Los streams se obtienen de: `https://video.casaaustin.pe/api/stream.mp4?src=cam{ID}`

Donde {ID} va del 101 al 1501 (incrementos de 100).

## GitHub Pages

Este repositorio está configurado para GitHub Pages. La aplicación se puede acceder en:

`https://[usuario].github.io/casa-austin-cameras/`

## Instalación Local

1. Clona el repositorio
2. Abre `index.html` en un navegador web
3. O usa un servidor local como Live Server

```bash
git clone https://github.com/[usuario]/casa-austin-cameras.git
cd casa-austin-cameras
# Abrir index.html en el navegador
```
