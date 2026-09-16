# Mercado inmobiliario · Santa Fe

Dashboard estático para GitHub Pages con filtros sobre la base de departamentos relevada el 16/09/2026.

## Archivos
- `index.html`: dashboard y lógica de filtros.
- `data.js`: base de publicaciones.
- `README.md`: estas instrucciones.

## Publicarlo en GitHub Pages
1. Crear un repositorio nuevo, por ejemplo `mercado-inmobiliario-santa-fe`.
2. Subir `index.html`, `data.js` y `README.md` a la raíz del repositorio.
3. En GitHub: **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar `main` y `/ (root)`, y guardar.
6. GitHub mostrará la URL pública del dashboard.

## Filtros incluidos
- búsqueda libre
- zona
- dormitorios
- baños
- cocheras
- condición
- precio USD mínimo/máximo
- USD/m² mínimo/máximo
- superficie mínima/máxima
- solo comparables Zeus
- solo Candioti
- solo productos desde USD 2.000/m²

Los KPI, el gráfico por zona y la tabla cambian en tiempo real.

## Actualizar datos
La forma más directa es reemplazar el contenido de `data.js` por una nueva base. El dashboard también permite cargar un CSV temporal desde el navegador y exportar los resultados filtrados.

> Nota: los datos son precios de oferta publicados, no precios de cierre.
