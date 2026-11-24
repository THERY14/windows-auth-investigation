# Windows Authentication Investigation

Laboratorio de análisis de registros para reconstruir una secuencia de autenticación Windows a partir de eventos sintéticos.

## Ejecutar el ejercicio

Abre [el CSV de ejemplo](data/events.csv) en GitHub, en una hoja de cálculo o en un editor de texto.

1. Ordena los eventos por hora UTC y separa los éxitos (4624) de los fallos (4625).
2. Agrupa por cuenta, equipo y origen. Calcula el intervalo entre el último fallo y el éxito asociado.
3. Documenta hechos, hipótesis y validaciones pendientes en una nota breve.

## Plantilla de trabajo

| Caso | Hora UTC | Evidencia | Prioridad provisional | Decisión y siguiente paso |
|---|---|---|---|---|
| | | | | |

Contrasta tus conclusiones con la [resolución de referencia](docs/walkthrough.md). Incluye una justificación cuando la decisión dependa de telemetría que aún falta.

## Alcance

Ejercicio de portafolio con datos sintéticos. Las prioridades y conclusiones corresponden al escenario del laboratorio.
