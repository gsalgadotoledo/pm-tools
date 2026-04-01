# 62 - Estimacion de Software y Velocity

## Por Que es Dificil Estimar Software

**Analogia del mecanico:**
- Mecanico BMW + carro BMW = estimacion precisa (lo ha hecho 1000 veces)
- Mecanico + carro custom hecho desde cero = "tal vez una semana?"

Software es como carros custom: cada codebase es unico y cambia constantemente.

## Story Points (No Horas)

En vez de "cuanto tiempo?" preguntar "**que tan dificil?**"

| Escala ejemplo | Facil | Medio | Dificil | Muy Dificil |
|---|---|---|---|---|
| 1-5 | 1 | 2-3 | 4 | 5 |
| Fibonacci | 1 | 3-5 | 8 | 13-21 |

> La escala no importa. La **consistencia** importa.

## Velocity

```
Sprint 1: 15 puntos completados → Velocity = 15
Sprint 2: 12 puntos → Velocity = 12
Sprint 3: 18 puntos → Velocity = 18
Sprint 4: 13 puntos → Velocity = 13
──────────────────────────────────────────
Velocity promedio = (15+12+18+13) / 4 = 14.5 puntos/sprint
```

**Ahora puedes predecir**: "Este epic tiene 29 story points → ~2 sprints → ~4 semanas"

## El Proceso

1. **Sprint planning**: Ingenieros estiman story points por ticket
2. **Multiples ingenieros** estiman (no solo uno)
3. **Rastrear velocity** por muchos sprints
4. **Promediar** → prediccion semi-precisa del trabajo futuro

---

## Mis Notas

-

---

| | |
|---|---|
| [<- Anterior: User Stories y Acceptance Criteria](61-user-stories-y-acceptance-criteria.md) | [Siguiente: Roadmapping ->](63-roadmapping.md) |
