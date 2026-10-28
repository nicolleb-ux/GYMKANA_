# GYMKANA — Una experiencia colectiva

Gymkana educativa digital, con estética inspirada en Windows 95/98. Tres equipos recorren tres destinos en distinto orden, responden oralmente a las portavoces de la actividad y reciben una letra por prueba. Al final ponen las nueve letras en común para interpretar una palabra.

## Publicación gratis en GitHub Pages

1. Crea un repositorio **público** en GitHub (por ejemplo, `gymkana`).
2. Sube **index.html** a la raíz del repositorio (Add file → Upload files). Puedes subir también este README.
3. Ve a **Settings → Pages**, selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)` y guarda.
4. La URL prevista será `https://TU-USUARIO.github.io/gymkana/` (sustituye usuario y nombre del repositorio según corresponda).

## Compatibilidad y privacidad

El sitio no necesita cámara, micrófono, instalación, registro, servicios externos ni bibliotecas. Funciona en navegadores modernos de ordenadores, teléfonos y tabletas, con ratón, teclado o pantalla táctil. También puede abrirse como archivo local una vez descargado. El avance se guarda solamente en `localStorage` del navegador, si está disponible; en navegación privada, al borrar datos, o al cambiar de dispositivo puede desaparecer. No se sincronizan respuestas entre dispositivos ni hay tratamiento remoto de datos.

## Configuración educativa

Las pistas y el orden están definidos en `LUGARES` y `RECORRIDOS` dentro de `index.html`. Las letras se distribuyen por rondas:

| Ronda | Grupo 1 | Grupo 2 | Grupo 3 |
|---|---|---|---|
| 1 | I | N | T |
| 2 | I | M | I |
| 3 | D | A | D |

En la puesta en común, leer por rondas intercalando grupos 1, 2 y 3 produce `INTIMIDAD`. Esta tabla es para las portavoces y no aparece en la web.

La app **no evalúa automáticamente** la respuesta del lugar: la casilla permite proponerlo y el botón OK se pulsa después de la validación oral. El alumnado puede pulsar OK sin autorización, por lo que la mediación presencial es parte de la dinámica.

## Accesibilidad

Hay etiquetas asociadas a los campos, navegación con teclado, indicadores de foco, botones táctiles amplios, anuncio de las letras para lectores de pantalla, soporte para preferencias de contraste y movimiento reducido. Conviene probar con los dispositivos del taller: no se garantiza idéntico comportamiento en todos los navegadores.
