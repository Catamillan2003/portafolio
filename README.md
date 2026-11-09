# Sitio web — Catalina Millán

Sitio personal responsive construido con HTML, CSS y JavaScript nativos. No requiere instalación de dependencias ni proceso de compilación.

## Archivos
- `index.html`: estructura y contenido del sitio.
- `styles.css`: diseño visual, responsive y animaciones.
- `script.js`: menú móvil, animaciones al desplazarse y año automático del footer.
- `assets/`: fotografías extraídas del portafolio suministrado.

## Probar localmente
Abre `index.html` en un navegador. Para una prueba local más fiel, ejecuta desde esta carpeta:

```bash
python3 -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Publicar
El sitio es estático y puede desplegarse directamente en Netlify, Vercel (Static), GitHub Pages o cualquier hosting que sirva archivos HTML. Sube la carpeta completa conservando la ruta `assets/`.

## Antes de producción
1. Verifica que el teléfono y correo publicados sean los que deseas hacer públicos.
2. Revisa que los periodos y cargos de experiencia estén actualizados.
3. Si quieres enlazar Instagram, LinkedIn o videos completos, agrega las URLs en `index.html`.
4. Las fotografías se tomaron de los PDF entregados para este desarrollo. Sustitúyelas por originales de mayor resolución si los tienes.

## Fuentes del contenido
La formación, experiencia, herramientas, idiomas y contacto se construyeron a partir de `Hoja de vida .pdf` y `Portafolio.pdf`. Cuando los documentos presentan diferencias en el semestre cursado, el sitio evita fijar un número y deja la carrera como "2023 — Actualidad". VOG Studio aparece en el portafolio, con periodo 2025–actualidad.
