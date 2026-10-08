# Portafolio de Orlando Díaz Ramírez

Portafolio personal de una sola página. Está publicado en https://orlando-diaz.vercel.app desde el repo https://github.com/Orlando-Diaz/portafolio. Vercel lo despliega solo cada vez que se hace push a `main`.

## Estructura
Todo está en `index.html`, sin frameworks y sin paso de build:
- `<style>`: los estilos. Los colores y las fuentes son variables en `:root`, con valores para el tema claro y para el oscuro.
- HTML: presentación, proyectos, tecnologías, formación y contacto.
- `<script>` al final: `PERFIL`, `ESTADOS` y `PROYECTOS` son los datos. El código de abajo los dibuja en la página y maneja el botón de tema.

## Cómo agregar o cambiar un proyecto
Copia un bloque de `PROYECTOS` y cambia sus datos. Un enlace con `url: ""` no se muestra.

## Convenciones
- Un solo archivo, sin dependencias ni build.
- Los colores se usan solo mediante las variables de `:root`, nunca como valores sueltos, para que funcionen los dos temas.
- Debe verse bien en un ancho de 400 px y sin scroll horizontal.
- Textos en español. Fuentes de Google Fonts: Archivo, Source Sans 3 e IBM Plex Mono.
- Los nombres de los proyectos deben coincidir con los de mi hoja de vida y mi LinkedIn: Mercadia (marketplace), Bolsillo (finanzas personales) y Fade (agenda para barberías).
- Los repos se llaman distinto: marketplace-backend y marketplace-frontend, gestor-finanzas y agenda-barber.

## Antes de publicar
- Comprueba que los enlaces de Demo y de código abren.
- Haz commit con Conventional Commits y push a `main`.
