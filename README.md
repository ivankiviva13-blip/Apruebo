# Permiso B Quest — primera versión

## Incluye
- iPhone-friendly responsive web app, estilo gamificado.
- Índice completo: 17 temas y anexo de puntos (18 unidades).
- Español por defecto y botón de traducción ucraniana en cada lección.
- 18 preguntas iniciales (una por unidad), feedback, XP, lista de errores y progreso local.
- Manifest y service worker básicos para añadir a pantalla de inicio y caché al alojarlo por HTTPS.

## Cómo probar en PC
Abre terminal en esta carpeta y ejecuta `python -m http.server 8000`, luego visita `http://localhost:8000`.

## Cómo instalar en iPhone
1. Aloja esta carpeta en un servicio HTTPS estático (por ejemplo GitHub Pages).
2. Abre la URL en Safari.
3. Pulsa Compartir → Añadir a pantalla de inicio.
4. Abre desde el icono. La caché offline depende de que la primera carga termine correctamente.

## Estado del contenido y cautelas
El manual de base aportado es la edición corregida de octubre de 2024. La app incluye estructura de las 18 unidades y resúmenes pedagógicos breves; no reproduce ni sustituye los 476 folios ni constituye cobertura exhaustiva. Las preguntas de esta versión son originales para practicar, no preguntas oficiales de examen.

DGT ha comunicado una reforma del Reglamento General de Circulación con entrada en vigor el 1 de octubre de 2026. Los contenidos afectados requieren una pasada de actualización tema por tema contra la norma vigente antes de considerar la app una fuente jurídica completa.

Fuentes oficiales de referencia:
- https://www.dgt.es/nuestros-servicios/permisos-de-conducir/obtener-un-nuevo-permiso-de-conducir/requisitos-preparacion-y-presentacion-a-examen/
- https://www.dgt.es/comunicacion/notas-de-prensa/20260930-reforma-del-reglamento-de-circulacion-usuarios-vulnerables/
- https://www.dgt.es/comunicacion/notas-de-prensa/20250610-el-gobierno-aprueba-la-actualizacion-del-catalogo-oficial-de-senales-de-trafico/
