# 62 - Software Estimation & Velocity

## Why Software Estimation is Hard

**The mechanic analogy:**
- BMW mechanic + BMW car = accurate estimate (done it 1000x)
- Mechanic + custom car built from scratch = "maybe a week?"

Software is like custom cars: every codebase is unique, constantly changing, and engineers haven't built this exact thing before.

## Story Points (Not Hours)

Instead of "how long?" ask "**how hard?**"

| Scale examples | Easy | Medium | Hard | Very Hard |
|---|---|---|---|---|
| 1-5 scale | 1 | 2-3 | 4 | 5 |
| Fibonacci | 1 | 3-5 | 8 | 13-21 |

> The scale doesn't matter. **Consistency** matters — always use the same one.

## Velocity

```
Sprint 1: Completed 15 story points → Velocity = 15
Sprint 2: Completed 12 story points → Velocity = 12
Sprint 3: Completed 18 story points → Velocity = 18
Sprint 4: Completed 13 story points → Velocity = 13
────────────────────────────────────────────────────
Average velocity = (15+12+18+13) / 4 = 14.5 points/sprint
```

**Now you can predict**: "This epic is estimated at 29 story points → ~2 sprints → ~4 weeks"

## The Process

1. **Sprint planning/scoping meeting**: Engineers estimate story points per ticket
2. **Multiple engineers** estimate (not just one)
3. **Track velocity** over many sprints
4. **Average it out** → semi-accurate prediction of future work
5. **More sprints tracked** = more accurate velocity

## Why Scrum > Kanban for Estimation

Scrum time-boxes work into sprints → you can calculate velocity. Kanban has no time boxes → harder to predict delivery dates.

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: User Stories & Acceptance Criteria](61-user-stories-and-acceptance-criteria.md) | [Next: Roadmapping ->](63-roadmapping.md) |
