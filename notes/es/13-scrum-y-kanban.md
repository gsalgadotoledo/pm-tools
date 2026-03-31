# 13 - Scrum & Kanban

Dos frameworks para implementar Agile en la practica.

## Scrum en 4 Pasos

### Paso 1: Sprint Planning Meeting

```
Product Backlog (todo el trabajo priorizado)
        |
        v  escoger lo mas importante
Sprint Backlog (trabajo para este sprint)
        |
        v  dividir en tickets
Herramienta de PM (Jira, etc.)
```

- Tomar los features mas importantes del **product backlog**
- Moverlos al **sprint backlog**
- Escribir todo el trabajo necesario como **tickets**

### Paso 2: El Sprint

- El trabajo se **encierra en un tiempo fijo** (usualmente **2 semanas**)
- El equipo toma tickets del sprint backlog y los mueve:

```
Por Hacer  →  En Progreso  →  Hecho
```

- Al final del sprint, items incompletos pasan al siguiente

### Paso 3: Daily Standup

- Reunion corta cada manana (**10-15 min**)
- De pie = se mantiene breve
- Cada persona responde 3 preguntas:
  1. En que trabaje **ayer**?
  2. En que trabajo **hoy**?
  3. Tengo algun **blocker** o necesito ayuda?

### Paso 4: Retrospectiva

- Reunion al **final de cada sprint**
- El PM guia al equipo con 3 preguntas:
  1. Que salio **bien**?
  2. Que **no** salio bien?
  3. Alguna **pregunta** o preocupacion?
- Asegura que los problemas se escuchen y el proceso mejore continuamente

---

## Resumen de Scrum

| Componente | Cuando | Duracion | Proposito |
|---|---|---|---|
| **Sprint Planning** | Inicio del sprint | 1-2 horas | Decidir que construir este sprint |
| **Sprint** | Continuo | 2 semanas (tipico) | Ciclo de desarrollo con tiempo fijo |
| **Daily Standup** | Cada manana | 10-15 min | Sync, blockers, colaboracion |
| **Retrospectiva** | Final del sprint | 30-60 min | Reflexionar: bueno, malo, preguntas |

---

---

## Kanban

Un framework Agile **menos estricto** — sin sprints, sin reuniones prescritas.

### Como Funciona

```
Product Backlog (lista priorizada infinita)
        |
        v  tomar siguiente tarea del top
En Progreso (WIP limitado)
        |
        v
Hecho → tomar siguiente tarea
```

### Diferencias Clave con Scrum

| | Scrum | Kanban |
|---|---|---|
| **Sprints** | Si (2-4 semanas) | No — flujo continuo |
| **Backlogs** | Product + Sprint backlog | Solo product backlog |
| **Reuniones** | Planning, standup, retro (prescritas) | Sin reuniones prescritas |
| **Limites WIP** | Implicitos (capacidad del sprint) | Explicitos — solo X items en progreso a la vez |
| **Estimacion** | Importante (velocity, story points) | Menos enfasis |
| **Mejor para** | Equipos que necesitan entrega predecible | Equipos con flujo continuo (ej: soporte) |

### Kanban Board

```
| Por Hacer | En Progreso (max 3) | Review (max 2) | Hecho |
|-----------|---------------------|----------------|-------|
| tarea     | tarea               | tarea          | tarea |
| tarea     | tarea               |                | tarea |
| tarea     |                     |                |       |
```

**WIP Limit**: solo un numero fijo de items pueden estar en cada columna a la vez.

### Ventaja y Desventaja

- **Ventaja**: Mas relajado, flexible, menos ceremonia
- **Desventaja**: Mas dificil estimar/proyectar tiempos de entrega (sin sprints = sin velocity)

### Cual es Mejor?

**No hay respuesta definitiva.** Depende de la preferencia de tu equipo. El mejor proceso es el que realmente usas.

---

## Buzzwords

| Termino | Definicion |
|---|---|
| **Scrum** | Framework Agile mas popular — sprints, standups, retros |
| **Kanban** | Framework Agile — flujo continuo, sin sprints, limites WIP |
| **Sprint** | Periodo de trabajo con tiempo fijo, usualmente 2 semanas |
| **Sprint Planning** | Reunion para decidir que entra en el sprint |
| **Sprint Backlog** | Subconjunto de trabajo seleccionado para el sprint actual |
| **Product Backlog** | Lista completa y priorizada de todo el trabajo por hacer |
| **Ticket** | Unidad de trabajo en una herramienta de project management |
| **Standup** | Reunion diaria de 10-15 min de sync (de pie) |
| **Retrospectiva** | Reunion de fin de sprint: que salio bien, que no, preguntas |
| **Time-boxing** | Restringir el trabajo a un periodo de tiempo fijo |

---

## Mis Notas

-

---

| | |
|---|---|
| [<- Anterior: Agile](12-agile.md) | [Siguiente: Waterfall ->](14-waterfall.md) |
