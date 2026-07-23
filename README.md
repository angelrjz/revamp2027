# Transformación Física 2026 — V2.2.1

PWA privada para registrar ejecución diaria, progreso corporal, entrenamiento de hipertrofia y revisión semanal.

Esta versión integra la rutina completa de Ángel, permite seleccionar **kg o lb por ejercicio** y conserva un historial por semanas calendario, de lunes a domingo.

## Publicación

Sube **el contenido de esta carpeta** a la raíz del repositorio conectado a Vercel:

- `index.html`
- `manifest.json`
- `service-worker.js`
- `vercel.json`
- carpeta `icons/`

Vercel publicará automáticamente el nuevo commit.

## Actualización en iPhone

Después del despliegue, abre la URL una vez en Safari con conexión. La V2 usa un caché nuevo y reemplaza la versión anterior. Si la app instalada sigue mostrando la anterior, ciérrala completamente y ábrela de nuevo.

## Datos

Los datos se guardan localmente en el dispositivo. En **SEMANA → Descargar respaldo** se genera un archivo JSON. Ese archivo puede restaurarse mediante **Importar**.

## Funciones V2

- Comidas planeadas, consumidas o modificadas.
- Recetario completo con 35 opciones, ingredientes, macros y tablas "Conoce tus platillos".
- Selector de platillos por nombre dentro de Hoy.
- Déficit diario exacto a partir del gasto energético total registrado.
- Promedio y déficit acumulado de los últimos siete días.
- Balance real contra 1,610 kcal y 120–130 g de proteína.
- Cierre diario: energía, hambre, estrés, recuperación y adherencia.
- Peso, cintura, grasa y masa magra.
- Entrenamiento por serie con carga en kg o lb, repeticiones y RIR.
- Rutina exacta Lower A, Upper A, Lower B y Upper B con series y rangos de repeticiones.
- Sección independiente RUTINAS con el programa completo visible en una sola vista.
- Plan semanal: squash, cuatro sesiones de fuerza, descanso y carrera de 10 km.
- La rutina del día se abre automáticamente y respeta ejercicios de 2, 3 o 4 series.
- Historial detallado de cargas, repeticiones y RIR por sesión.
- Lectura semanal.
- Exportación e importación de respaldo.
- Fechas locales, sin depender de UTC.
