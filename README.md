# 🎯 Auditoría de Dolores

Copiloto de bolsillo para la **visita de descubrimiento** a un negocio local: te dicta qué
preguntar (playbook completo), captura respuestas con 2 toques, calcula cuánta plata pierde
el negocio al mes en tareas repetitivas y genera el diagnóstico + mensaje de seguimiento
por WhatsApp con la oferta de asesoría.

- **Un solo archivo** (`index.html`), sin dependencias, funciona offline.
- **Datos 100% locales**: las visitas viven en el `localStorage` del teléfono; nada se sube.
- Respaldo por export/import JSON.
- Botón 🆘 con "preguntas asesinas" para cuando la conversación se estanca.
- Basado en el playbook de descubrimiento propio (fases rapport → bloques A-E → propuesta,
  red/green flags) con el giro comercial de vender **resultados** (tiempo y plata), no tecnología.

## Uso

Abrir la página en el celular, `➕ Nueva visita`, y seguir lo que dice la pantalla.
Al final: `Enviar resumen por WhatsApp` el mismo día de la visita.

El valor hora para el cálculo de pérdidas se cambia en ⚙️ (default $8.000 CLP).
