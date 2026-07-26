# Transformación Física 2026 — V2.3.0

PWA privada para registrar ejecución diaria, progreso corporal, entrenamiento de hipertrofia y revisión semanal.

Esta versión convierte la rutina de Ángel en un bloque intencional de seis semanas, equilibra el tren superior, permite seleccionar **kg o lb por ejercicio** y conserva el historial anterior sin migraciones destructivas.

## Publicación

Sube **el contenido de esta carpeta** a la raíz del repositorio conectado a Vercel:

- `index.html`
- `manifest.json`
- `service-worker.js`
- `vercel.json`
- carpeta `icons/`

Vercel publicará automáticamente el nuevo commit.

## Actualización en iPhone

Después del despliegue, abre la URL una vez en Safari con conexión. La V2.3 usa un caché nuevo y reemplaza los archivos de la versión anterior. Si la app instalada sigue mostrando la anterior, ciérrala completamente y ábrela de nuevo.

## Datos

Los datos se guardan localmente en el dispositivo con la misma clave `transformacion2026_v2`. En **SEMANA → Descargar respaldo** se genera un archivo JSON. Ese archivo puede restaurarse mediante **Importar**.

Actualizar a V2.3 no elimina mediciones, comidas ni entrenamientos. Las sesiones guardadas anteriormente se muestran como **V1**; las nuevas sesiones incluyen identificadores estables por ejercicio y se muestran como **V2**. Antes de importar otro archivo, la app descarga automáticamente un respaldo preventivo.

## Cambios de rutina en V2.3

- Upper A mantiene la prioridad de pecho y hombro, e incorpora remo horizontal.
- Upper B pasa a ser dominante de espalda, bíceps y deltoide posterior, con pecho secundario.
- El salto explosivo se detiene cuando cae la altura o velocidad; ya no se prescribe al fallo.
- Cada rutina muestra intención, esfuerzo objetivo y descansos.
- Cada ejercicio muestra propósito, clave técnica y siguiente acción de progresión.
- La progresión doble indica cuándo mantener la carga o subir entre 2.5% y 5%.
- Lower B mantiene la exposición de fuerza con 2–3 RIR para controlar fatiga antes del 10K.

## Funciones

- Comidas planeadas, consumidas o modificadas.
- Recetario completo con 35 opciones, ingredientes, macros y tablas "Conoce tus platillos".
- Selector de platillos por nombre dentro de Hoy.
- Déficit diario exacto a partir del gasto energético total registrado.
- Promedio y déficit acumulado de los últimos siete días.
- Balance real contra 1,610 kcal y 120–130 g de proteína.
- Cierre diario: energía, hambre, estrés, recuperación y adherencia.
- Peso, cintura, grasa y masa magra.
- Entrenamiento por serie con carga en kg o lb, repeticiones y RIR.
- Rutina Lower A, Upper A, Lower B y Upper B con series, rangos, RIR, intención y progresión.
- Sección independiente RUTINAS con el programa completo visible en una sola vista.
- Plan semanal: squash, cuatro sesiones de fuerza, descanso y carrera de 10 km.
- La rutina del día se abre automáticamente y respeta ejercicios de 2, 3 o 4 series.
- Historial detallado de cargas, repeticiones y RIR por sesión, identificado como V1 o V2.
- Lectura semanal.
- Exportación e importación de respaldo.
- Fechas locales, sin depender de UTC.
