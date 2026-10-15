# TORO: Construye la academia

Juego educativo en Unity 6000.3.25f1: mapa 3D isométrico y laboratorios 2D para construir una base de datos.

[Jugar en el navegador](https://odsanchezuniversitaria-web.github.io/toro-rescate-datos/)

Ocho niveles: requisitos, campos y claves, relaciones, normalización, creación de tablas, carga de registros, consultas e integración de la academia. Cada construcción puede probarse y repararse. Incluye SQL descargable, voces en español, efectos, progreso guardado, medallas, puntuación y récords locales.

El contenido adapta el esquema de 14 tablas del taller TORO con datos ficticios. El laboratorio simula operaciones relacionales limitadas; no es un servidor MySQL ni un editor SQL general. El arcade de disparos y saltos permanece como actividad opcional.

## Controles

PC: seleccionar piezas y destinos con el ratón; probar la construcción y consultar el plano o SQL. En el mapa, elegir un edificio y entrar al nivel disponible.

Celular: horizontal y botones táctiles.

WebXR: entrar en VR desde un navegador y visor compatibles, navegar botones con el stick y confirmar con el gatillo. El progreso del laboratorio se conserva al salir de VR.

El progreso y los récords se guardan en este navegador. Borrar sus datos elimina ese guardado. Las pruebas de teléfono y visor son emuladas; no sustituyen comprobaciones en hardware físico.

## Publicación

Este repositorio contiene exclusivamente el build web en `site/` y el workflow de GitHub Pages. No incluye el PDF, datos personales ni el proyecto fuente. Cada cambio en main publica el sitio mediante GitHub Actions.
