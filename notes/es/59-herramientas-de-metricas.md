# 59 - Herramientas de Metricas

## Herramientas de Analitica y Tracking

| Herramienta | Que hace | Mejor para | Costo |
|---|---|---|---|
| **Google Analytics** | Tracking web + mobile, trafico, comportamiento de usuario | Todos — empieza aqui | Gratis |
| **Crazy Egg** | Datos de clicks, mapas de calor, scroll maps, movimiento de mouse | Entender donde clickean y miran los usuarios en tu sitio | Pago |
| **KISSmetrics** | Metricas custom, calculos, graficas, web + mobile | Analitica profunda con metricas personalizadas | Caro |
| **Mixpanel** | Comportamiento individual de usuario, web + mobile, integracion email/push | Analitica a nivel usuario + campanas de retencion | Caro |
| **Optimizely** | A/B testing + tracking de clicks | Probar cual version funciona mejor | Freemium |

## El Hub: Segment

**Problema**: Cada herramienta de analitica requiere codigo en tu sitio. Cambiar herramientas = cambiar codigo + perder datos historicos.

**Solucion**: Segment es un **hub de metricas**.

```
Tu App/Sitio → Segment → Google Analytics
                       → Mixpanel
                       → KISSmetrics
                       → Cualquier otra herramienta
```

- Conecta tu app a Segment **una vez**
- Conecta/desconecta cualquier herramienta sin cambiar tu codigo
- Mantiene backup de tus datos
- Prueba herramientas sin perder historial

> Configura Segment **primero**, luego prueba diferentes herramientas a traves de el.

---

> **Ver [Herramientas 2026](tools-2026-actualizacion.md)** — KISSmetrics desvanecido, Amplitude/PostHog son los nuevos lideres, Microsoft Clarity ofrece heatmaps gratis, y todas las herramientas ahora tienen consultas con AI.

## Mis Notas

-

---

| | |
|---|---|
| [<- Anterior: AARRR Metricas Pirata](58-aarrr-metricas-pirata.md) | Siguiente: ... -> |
