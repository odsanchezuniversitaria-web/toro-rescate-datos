# TORO: Construye la academia

Juego educativo en Unity 6000.3.25f1: mapa 3D isométrico y laboratorios 2D para construir una base de datos.

[Jugar en el navegador](https://odsanchezuniversitaria-web.github.io/toro-rescate-datos/?v=2.3.1)

Ocho niveles: requisitos, campos y claves, relaciones, normalización, creación de tablas, carga de registros, consultas e integración de la academia. Cada construcción puede probarse y repararse. Incluye un tutorial práctico, enseñanza al entrar en cada nivel y pistas progresivas que explican y señalan el siguiente paso sin quitar puntos. No usa cuestionarios. Incluye SQL descargable, voces en español, efectos, progreso guardado, medallas, puntuación y récords locales.

El contenido adapta el esquema de 14 tablas del taller TORO con datos ficticios. El laboratorio simula operaciones relacionales limitadas; no es un servidor MySQL ni un editor SQL general. El arcade de disparos y saltos permanece como actividad opcional.

El mapa también ofrece CIRCUITOS: tres rondas para unir nueve relaciones mediante cables. Cada ronda completada permite repetir o continuar.

## Controles

PC: toca las estaciones móviles para disparar los paquetes del nivel 1. En los demás talleres, selecciona piezas y destinos con el ratón; probar la construcción y consultar el plano o SQL. En el mapa, elegir un edificio y entrar al nivel disponible.

Celular: horizontal y botones táctiles.

WebXR: entrar en VR desde un navegador y visor compatibles, apuntar a los botones o blancos con el mando y pulsar el gatillo. El progreso del laboratorio se conserva al salir de VR.

El progreso y los récords se guardan en este navegador. Borrar sus datos elimina ese guardado. Las pruebas de teléfono y visor son emuladas; no sustituyen comprobaciones en hardware físico.

## Publicación

Este repositorio contiene exclusivamente el build web en `site/` y el workflow de GitHub Pages. No incluye el PDF, datos personales ni el proyecto fuente. Cada cambio en main publica el sitio mediante GitHub Actions.



## 2.3.0 · Lanzador de datos y pruebas de niveles (2026-10-16)

El nivel 1 de la campaña sustituye la lista de clasificación por una arena de disparo: los 14 paquetes reales de TORO viajan a cinco estaciones móviles. Tocar el blanco (o apuntar con el mando XR y pulsar el gatillo) dispara un proyectil guiado; al impactar se valida la función de la tabla. Un destino incorrecto conserva el paquete, rompe la racha y explica el error. Las pistas son gratuitas. No hay cuestionario de selección de respuestas ni límite de tiempo. La construcción alimenta el mismo modelo y SQL de la campaña.

Cada nivel verificado muestra Repetir nivel / Siguiente nivel. Repetir usa una copia de práctica y conserva la campaña; al continuar se recupera el avance guardado. El menú principal abre el mapa de campaña y mantiene el minijuego de circuitos accesible desde él.

Desarrollador, en el menú inicial, abre un teclado accesible con toque o rayos XR. El código 1508 habilita los ocho niveles con sus prerrequisitos válidos en una partida temporal. No modifica el guardado de campaña ni sus récords. Salir al menú o recargar termina ese modo. Es una comodidad de pruebas local, no un mecanismo de seguridad.

El nivel 1 conserva voz en español, efectos de impacto, partículas y feedback contextual. Los demás siete niveles conservan sus mecánicas de construcción existentes.


## 2.3.1 · Créditos

La pantalla de inicio incluye: hecho por Oscar Sanchez y Angie Fajardo. Visible en PC, celular y el menú inmersivo.
