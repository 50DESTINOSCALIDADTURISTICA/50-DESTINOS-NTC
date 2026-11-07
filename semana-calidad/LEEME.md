# Repositorio de piezas: Semana Nacional de la Calidad Turística 2026

Sitio estático para publicar en GitHub Pages (por ejemplo, en la carpeta `semana-calidad/` del repositorio del portal 50 Nuevos Destinos).

## Cómo publicarlo
1. Copia la carpeta completa dentro del repositorio, sin cambiar la estructura.
2. Sube los cambios. La dirección queda como `.../semana-calidad/`.
3. Agrega un botón en el landing que enlace a esa dirección.

## Estructura
- `index.html`: la página.
- `data/registros.js`: base oficial (642 registros) con nombre, tipo, ubicación y norma. No incluye correos ni responsables.
- `data/destinos.js`: los 49 destinos y sus publicaciones.
- `data/contenidos.js`: textos sugeridos, títulos y textos alternativos por ruta.
- `piezas/<destino>/`: piezas en JPG (`p<publicación>-<pieza>.jpg`), miniaturas en `t/` y video cuando existe.
- `assets/`: tipografía, logos, personajes, fondos de la plantilla y JSZip.

## Logos de alcaldía pendientes
Las piezas de Aguadas, Nuquí, Pijao, Roldanillo y Puerto Carreño llevan por ahora solo los logos institucionales. Cuando se tengan los logos oficiales de esas alcaldías se agregan en la barra de logos con el mismo nombre de archivo.

## Cómo actualizar la base
La base se regenera desde el Excel oficial con el mismo procedimiento usado para esta versión (normalización de normas y unión de registros repetidos). Pide la actualización con el Excel nuevo.

## Acceso
El buscador solo muestra destinos y organizaciones de la base oficial; al elegir uno se abren sus piezas. Cada pieza generada lleva un código (por ejemplo, `SNCT2026-R0255`) que permite saber de qué registro salió.
