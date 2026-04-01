# 56 - Elegir Buenas Metricas

## Las Metricas Suben en Cascada

Tu metrica de equipo alimenta la metrica a nivel empresa:

```
Meta de empresa: Aumentar tiempo en Facebook
    ↓
Tu equipo: Aumentar comentarios/persona en 5%
    (porque personas que comentan mas se quedan mas)
```

Puede que no rastrees la metrica top directamente — rastreas lo que la **impulsa**.

## Metricas Exploratorias vs de Reporte

| | Exploratorias | De Reporte |
|---|---|---|
| **Proposito** | Buscar pistas, investigar comportamiento | Rastrear salud del producto en el tiempo |
| **Duracion** | Ad-hoc, temporales | Largo plazo, consistentes |
| **Audiencia** | Tu y tu equipo | Jefe, inversionistas, la empresa |
| **Ejemplo** | Cuantas personas clickean boton X en pagina Y | MAU, tasa de retencion |

## Que Hace una Buena Metrica?

### 1. Entendible
- Explicable solo con decir su nombre
- Usualmente: algo ÷ algo = porcentaje, o conteo de X por usuario
- NO: "personas que clickearon boton A dos veces, regresaron y clickearon B"

### 2. Tasa o Ratio (no numero crudo)
| Mala metrica | Buena metrica | Por que |
|---|---|---|
| Total usuarios historico | MAU (Monthly Active Users) | El total crudo siempre sube — esconde problemas |
| Total noches reservadas (Airbnb) | Promedio noches/persona/mes | Total crudo afectado por marketing, economia, etc. |

### 3. No Basada en Falsa Correlacion
> Ventas de helado y muertes por ahogamiento suben en verano — no significa que el helado causa ahogamientos.

Asegurate de que tus metricas realmente **se impactan mutuamente**, no solo se rastrean juntas por coincidencia.

### 4. Cambiable por Tu Equipo
Elige metricas que los cambios de tu producto realmente puedan mover.

| Escenario | Mala metrica | Mejor metrica |
|---|---|---|
| Usuarios solo tienen 2 hrs/dia | Tiempo en app (limitado) | Logins por semana, sesiones por semana |
| E-commerce: usuarios compran 1x/mes | Compras por mes (estancado en 1) | Valor promedio de orden por visita |

## Checklist Resumen

- [ ] Cualquiera puede entenderla solo por el nombre?
- [ ] Es una tasa/ratio, no un numero crudo?
- [ ] Estamos seguros de que la correlacion es causal, no coincidencia?
- [ ] El trabajo de nuestro equipo puede realmente cambiar esta metrica?

---

## Mis Notas

-

---

| | |
|---|---|
| [<- Anterior: Categorias de Metricas](55-categorias-de-metricas.md) | Siguiente: ... -> |
