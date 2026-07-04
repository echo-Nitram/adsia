# Alertas proactivas ante caídas de ROAS o fatiga creativa — plan Pro

## Qué es

Un aviso que Claude manda apenas detecta un problema en una campaña — sin esperar al reporte mensual ni a que el cliente pregunte. La idea es que el cliente se entere a tiempo de actuar, no cuando ya perdió presupuesto.

## Qué dispara una alerta

- **Caída de ROAS:** una campaña cae por debajo de 1x (gasta más de lo que genera), o cae más de un 30% respecto a su propio promedio de las últimas dos semanas.
- **Fatiga creativa:** frecuencia promedio de la audiencia por encima de 6-7 impactos, o caída de CTR mayor al 30% en pocos días.
- **Otras señales relevantes:** presupuesto de una campaña por agotarse mucho antes de lo previsto, o un error de sincronización del catálogo que esté afectando campañas dinámicas.

## Formato del mensaje

Corto, por WhatsApp, con esta estructura:

1. Qué se detectó y en qué campaña.
2. El dato concreto detrás (no solo "hay un problema" — el número que lo justifica).
3. Una recomendación puntual.

**Ejemplo:**

> ⚠️ Alerta ADSIA — Campaña "Retargeting web"
> ROAS cayó a 1.1x (venía en 2.3x la semana pasada). Tu audiencia ya vio el anuncio en promedio 7.8 veces — está quemado.
> Recomiendo renovar el creativo o pausarla y redirigir presupuesto a "Catálogo otoño" (ROAS 3.4x esta semana).
> ¿Querés que lo charlemos por acá o lo dejamos para tu próximo check-up?

## Protocolo de respuesta

Igual que en toda la relación con Claude: **la alerta es un aviso, no una acción.** Nada se pausa ni se reasigna solo. El cliente puede:

- Responder directamente en Claude pidiendo el contexto completo antes de decidir: *"Me llegó una alerta de [problema] en [campaña], ¿qué me recomendás?"*
- Guardarlo para su próximo check-up si no es urgente.
- Pedir que ADSIA lo acompañe en la decisión por WhatsApp si tiene dudas.

## Frecuencia y ruido

Para que las alertas se tomen en serio y no se ignoren por exceso:

- Máximo una alerta por campaña por semana, salvo un problema nuevo y distinto.
- Si el mismo día se detectan varias señales, se agrupan en un solo mensaje en vez de mandar varios.
- Las alertas resueltas o descartadas por el cliente quedan resumidas en el reporte mensual (`reportes-mensuales.md`), no se repiten.
