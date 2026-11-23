# Expo TecNOA 2026 · Innovación desde nuestra tierra

Landing de la Expo TecNOA 2026: trabajos de campo de Sistemas de Información
(Ing. Informática · Lic. en Sistemas · Ing. Industrial) de la Facultad de Ingeniería – UNJu.

- **Cuándo:** miércoles 2 de diciembre de 2026, 18 h
- **Dónde:** instalaciones de la UNJu, Canónigo Gorriti 237

## Estructura
- `index.html`: la página completa (HTML + CSS en línea + un poco de JavaScript para el filtro por eje y la cuenta regresiva).
- `assets/`: mascota y logos.

## Publicar con GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
La página queda en `https://valentinaestrella0.github.io/expotecnoa2026/`.

## Fotos de los grupos
Cada tarjeta muestra una foto de ejemplo. Para poner la foto real, subí la imagen como
`assets/fotos/grupo-N.jpg` (por ejemplo `assets/fotos/grupo-11.jpg`), horizontal, idealmente 1200 × 675 px.
Apenas el archivo existe, reemplaza al ejemplo.

## Proyectos ocultos hasta el día de la Expo
La sección muestra "Muy pronto…" y revela los proyectos el 2 de diciembre a las 18 h, cuando termina la cuenta regresiva.
Para verlos antes, agregá `?previa` a la dirección: `https://valentinaestrella0.github.io/expotecnoa2026/?previa`.
Ojo: el ocultamiento es visual; quien mire el código fuente puede leer el contenido.

## Agregar o editar un proyecto
Cada proyecto es un bloque `<article class="proyecto" data-eje="0X">` dentro de la sección `#proyectos` de `index.html`.
Copiá uno, cambiá el número de grupo, el equipo, la descripción y el eje (`01` a `04`).
