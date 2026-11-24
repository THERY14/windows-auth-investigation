# Resolución de referencia

| Hora UTC | Evidencia | Interpretación |
|---|---|---|
| 10:28:14 a 10:29:02 | Tres eventos 4625 para lab-user en lab-ws-04 desde 192.0.2.45 | Tres intentos de inicio de sesión fallidos. |
| 10:29:25 | Evento 4624 con la misma cuenta, host y origen | Inicio de sesión exitoso 23 segundos después del último fallo. |
| 10:29:37 | Evento 4624 para otra cuenta, host y origen | Queda fuera de la secuencia correlacionada. |

### Nota de investigación

Los cuatro eventos principales abarcan 71 segundos y tienen tipo de inicio de sesión 3, correspondiente a acceso de red. Los datos admiten explicaciones como reintentos legítimos o uso indebido de credenciales. Para distinguirlas, revisar si el origen es habitual, validar actividad con el usuario y ampliar la ventana de búsqueda para la misma cuenta. Antes de atribuir el acceso, confirmar el contexto con los registros originales. La dirección 192.0.2.45 se usa como ejemplo de documentación.

Fuente del ejercicio: [eventos sintéticos](../data/events.csv).
