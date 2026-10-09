# TORO: Rescate de Datos

Juego educativo de acción con estética tecnológica, creado en Unity 6000.3.25f1.

**Jugar:** https://odsanchezuniversitaria-web.github.io/toro-rescate-datos/

Recupera datos, salta obstáculos, destruye drones y protege la integridad de una academia virtual. Incluye tres sectores, jefe final, combos, partículas, música y voces en español. Las situaciones del juego representan conceptos de bases de datos mediante una simulación.

## Controles de escritorio

- A/D o flechas: cambiar de carril.
- Espacio: saltar y doble salto.
- J o clic sostenido: disparar.
- E: pulso.
- Esc: pausa.

La página ofrece la interacción disponible para el dispositivo y navegador. Para el modo Web VR se necesita un navegador con WebXR y un visor compatible; la página se sirve mediante HTTPS.

## Celular

Gira a horizontal y usa las flechas, SALTO x2, FUEGO y PULSO. Puedes mantener el disparo mientras saltas con otro dedo. La página recomienda girar cuando está en vertical.

## Visor WebXR

Pulsa ENTRAR EN VR desde el navegador del visor. Gatillo para iniciar/disparar/reintentar, stick para cambiar de carril, A/X para saltar, B/Y para pulso y agarre izquierdo para pausar o continuar. Al salir de VR la partida vuelve a 2D en pausa. El personaje salta; la plataforma de observación permanece fija.

Las pruebas automatizadas de VR utilizan IWER con Meta Quest 3 emulado; no representan una validación con un visor físico. Las licencias de terceros se incluyen en `site/ThirdPartyNotices.txt`.

## Publicación

Este repositorio contiene únicamente los archivos compilados para navegador, en `site/`, y el workflow de GitHub Pages. El proyecto de Unity, el PDF de referencia y los archivos locales de validación no forman parte de la publicación.

Cada cambio en `main` publica `site/` mediante GitHub Actions. La configuración de Pages usa **GitHub Actions** como origen.
