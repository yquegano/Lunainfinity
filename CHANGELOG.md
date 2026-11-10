# Historial de cambios — Luna Infinity

Regla: antes de cada cambio se guarda una copia fechada en `versiones/` y el detalle queda en Notion.

## 2026-11-10 · v10.1 — Reparación de la voz y de «Construye la oración» (aprobada por Jotha)
- **Botones 🔊 (inglés) y 🇪🇸🔊 (español):** no hacían nada porque la v10 no tenía ningún código de voz (`speak` y `speakES` no existían). Ahora leen con la mejor voz del equipo (inglés de EE. UU.; español de Chile o latinoamericano). Probado: los 322 botones de las lecciones hablan (241 en inglés, 81 en español).
- **Ejercicio «Construye la oración»:** además de faltar `selectTile`, `checkBuild` y `clearBuild`, la práctica se quedaba en blanco al llegar a este ejercicio porque faltaba la función `shuffle`. Ahora se tocan las palabras en orden, se quitan tocándolas en la oración, «Limpiar» reinicia y «Verificar» corrige (muestra la respuesta si está mal y la lee en voz alta si está bien). Probado en los 59 ejercicios de 44 lecciones: 59/59 correctos aceptados y 59/59 incorrectos rechazados.
- Respaldos: antes = `versiones/LunaInfinity_2026-06-26_v10.html` (idéntica a la publicada); después = `versiones/LunaInfinity_2026-11-10_v10.1_voz-y-construye-la-oracion.html`.
- Para volver atrás: copiar el archivo «antes» sobre `index.html`.

## 2026-11-09 · Se publica la versión 10 (versión principal)
- `index.html` pasa a ser la **v10** (26 jun 2026, 245 KB), que estaba solo en el computador (Escritorio/PROYECTOS/05_LUNA_APPS_INGLES/luna_infinity).
- Respaldos: `versiones/LunaInfinity_2026-06-26_v9_antes-publicada.html` (la que estaba publicada, 183 KB) y `versiones/LunaInfinity_2026-06-26_v10.html`.
- Niveles A1 → C2 y curso ESP115 (inglés para diseño).
- Se cierra la tarea #52 de Notion: subir la última versión de Luna.
