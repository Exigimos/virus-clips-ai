# VIRUS CLIPS AI — MVP inicial

Esta es una primera versión pública y estática del proyecto. Incluye:
- Interfaz adaptable a móvil y computadora.
- Selección de videos locales y vista previa.
- Selección manual de inicio y final.
- Exportación de fragmentos mediante MediaRecorder cuando el navegador lo soporta.
- Campo de enlace de YouTube con validación básica (no descarga ni procesa el enlace).

## Ejecutar
Abre `index.html` en un navegador moderno. Para mejores resultados de captura/exportación, prueba Chrome o Firefox en escritorio. En iPhone/Safari la compatibilidad de `captureStream` y `MediaRecorder` puede variar.

## Publicar gratis
Puedes subir esta carpeta a GitHub y activar GitHub Pages, o arrastrarla a Netlify Drop. Es una web estática: no necesita servidor para esta prueba.

## Lo que falta para la versión completa
1. Backend seguro para recibir/procesar archivos grandes.
2. Integración de transcripción y análisis de momentos mediante IA.
3. Subtítulos editables y render vertical 9:16 real.
4. Importación de fuentes de video mediante APIs autorizadas; un enlace de YouTube no se puede convertir en archivo directamente desde esta página. Respeta permisos, derechos de autor y condiciones de la plataforma.
5. Autenticación, límites de uso, cola de trabajos y almacenamiento si la plataforma será pública a escala.

No hay API keys ni servicios de pago incluidos. No se debe anunciar todavía como detector automático de clips con IA: esta versión es un editor de recortes manual.
