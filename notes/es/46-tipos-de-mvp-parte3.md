# 46 - Tipos de MVP (Parte 3): Concierge, Piecemeal, Wizard of Oz

## 6. Concierge MVP

Ayudar **manualmente** a los usuarios a lograr la tarea que tu producto haria.

| Aspecto | Detalle |
|---|---|
| **Como** | Ofrecer un "programa beta" a un grupo pequeno, luego personalmente guiarlos en la tarea |
| **Por que** | Ver de primera mano si lo que estas construyendo es util y necesario |
| **Ejemplo: Amazon bot** | En vez de construir un algoritmo, enviar recomendaciones personalizadas por email manualmente |
| **Ejemplo: Rent the Runway** | Ayudaron fisicamente a mujeres en campus universitarios a escoger, organizar y devolver vestidos elegantes antes de construir la plataforma |

---

## 7. Piecemeal MVP

Unir **herramientas existentes** para simular tu producto.

| Herramienta | Que hace |
|---|---|
| Weebly / Wix / Squarespace | Crear paginas, tomar ordenes |
| Formstack / Typeform / Jotform | Forms avanzados y calculos |
| Twilio | Enviar mensajes de texto, construir sistemas SMS |
| Recurly | Gestionar suscripciones |
| WordPress | Sitio completo con plugins |

**Ejemplo: Groupon** (originalmente "The Point")
- Sitio construido en **WordPress**
- Ordenes disparaban emails via **Apple Mail + AppleScript**
- AppleScript auto-generaba cupones y los enviaba de vuelta
- Sin backend complejo

---

## 8. Wizard of Oz MVP

El front-end se ve **completamente funcional**, pero un humano hace todo manualmente detras de escena.

```
Usuario ve:    App hermosa y funcional
Realidad:      Persona detras de la cortina cumpliendo requests manualmente
```

| Aspecto | Detalle |
|---|---|
| **Por que** | El mayor esfuerzo de dev es logica server-side que nadie ve — saltatela |
| **Como** | Construir front-end real, tener a alguien cumpliendo manualmente en el backend |
| **Ejemplo** | Red social boton "Match Me" — alguien revisa perfiles manualmente y envia matches por email |
| **Ejemplo Clasico: Zappos** | Tienda de zapatos online, sin inventario. Cuando alguien ordenaba, cruzaban la calle, compraban los zapatos y los enviaban |

---

## Resumen Completo de Tipos de MVP

| # | Tipo | Esfuerzo | Que es falso | Ejemplo |
|---|---|---|---|---|
| 1 | **Email** | Mas bajo | Todo | AppSumo |
| 2 | **Shadow Button** | Bajo | El feature | Tests de boton de login |
| 3 | **404 / Coming Soon** | Bajo-Medio | La pagina del producto | Amazon, Oculus Rift |
| 4 | **Video Explainer** | Medio | El demo | Dropbox |
| 5 | **Landing Page** | Medio | El producto | Buffer, Basecamp |
| 6 | **Concierge** | Medio | Automatizacion (labor manual) | Rent the Runway |
| 7 | **Piecemeal** | Medio | Desarrollo custom | Groupon (WordPress + AppleScript) |
| 8 | **Wizard of Oz** | Medio-Alto | Backend/logica de servidor | Zappos |

---

## Mis Notas

-

---

| | |
|---|---|
| [<- Anterior: Tipos de MVP Parte 2](45-tipos-de-mvp-parte2.md) | Siguiente: ... -> |
