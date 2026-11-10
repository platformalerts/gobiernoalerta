# Archivo de capturas de @GobiernoAlerta

Archivo público de pantallazos de publicaciones de X de las cuentas seguidas por [@GobiernoAlerta](https://x.com/GobiernoAlerta), mantenido por PlatformAlerts.

Cada captura se publica en su propia carpeta fechada dentro de `captures/`, acompañada de:

- `screenshot.png`: imagen original entregada por Microlink, sin edición ni recompresión posterior.
- `metadata.json`: origen, fechas UTC, configuración de captura, dimensiones y huella SHA-256.
- `README.md`: explicación legible de cómo y cuándo se obtuvo esa imagen.

La fecha de la carpeta indica cuándo terminó el guardado local. La fecha de publicación del tuit, la solicitud de captura y la preparación de la ficha se registran por separado. Microlink puede devolver una imagen de caché; cuando la hora exacta de renderizado o el estado de caché no están disponibles, se indican como desconocidos. La primera publicación de cada carpeta puede consultarse en el historial de commits.

Las ventanas emergentes de X se ocultan antes de la captura. El encuadre puede incluir respuestas y publicaciones cercanas, y puede dejar contenido fuera de pantalla. Los vídeos se representan con una imagen estática. Las fichas de capturas anteriores a este publicador señalan expresamente cuándo su configuración fue reconstruida a partir del recolector utilizado.

Las publicaciones automáticas añaden carpetas nuevas y conservan las anteriores. Cada lote incorpora conjuntamente la imagen, los metadatos y el README. La huella SHA-256 permite comprobar la integridad de la imagen; no es una certificación independiente de su fecha de captura.
