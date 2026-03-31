# 13 - Scrum & Kanban

Two frameworks for implementing Agile in practice.

## Scrum in 4 Steps

### Step 1: Sprint Planning Meeting

```
Product Backlog (all prioritized work)
        |
        v  pick most important items
Sprint Backlog (work for this sprint)
        |
        v  break into tickets
Project Management Tool (Jira, etc.)
```

- Take the most important features from the **product backlog**
- Move them to the **sprint backlog**
- Write out all work needed as **tickets**

### Step 2: The Sprint

- Work is **time-boxed** into a sprint (usually **2 weeks**)
- Team picks tickets from sprint backlog and moves them:

```
To Do  →  In Progress  →  Done
```

- At end of sprint, incomplete items roll to next sprint

### Step 3: Daily Standup

- Short meeting every morning (**10-15 min**)
- Standing up = keeps it brief
- Each person answers 3 questions:
  1. What did I work on **yesterday**?
  2. What am I working on **today**?
  3. Do I have any **blockers** or need help?

### Step 4: Retrospective

- Meeting at the **end of each sprint**
- PM leads the team through 3 questions:
  1. What went **well**?
  2. What did **not** go well?
  3. Any **questions** or concerns?
- Ensures issues are heard and process improves continuously

---

## Scrum Summary

| Component | When | Duration | Purpose |
|---|---|---|---|
| **Sprint Planning** | Start of sprint | 1-2 hours | Decide what to build this sprint |
| **Sprint** | Continuous | 2 weeks (typical) | Time-boxed development cycle |
| **Daily Standup** | Every morning | 10-15 min | Sync, blockers, collaboration |
| **Retrospective** | End of sprint | 30-60 min | Reflect: good, bad, questions |

---

---

## Kanban

A **less strict** Agile framework — no sprints, no prescribed meetings.

### How it Works

```
Product Backlog (endless prioritized list)
        |
        v  take next task from top
In Progress (limited WIP)
        |
        v
Done → take next task
```

### Key Differences from Scrum

| | Scrum | Kanban |
|---|---|---|
| **Sprints** | Yes (2-4 weeks) | No — continuous flow |
| **Backlogs** | Product + Sprint backlog | Product backlog only |
| **Meetings** | Planning, standup, retro (prescribed) | No prescribed meetings |
| **WIP Limits** | Implicit (sprint capacity) | Explicit — only X items in progress at once |
| **Estimation** | Important (velocity, story points) | Less emphasis |
| **Best for** | Teams needing predictable delivery | Teams with continuous flow (e.g., support) |

### Kanban Board

```
| To Do | In Progress (max 3) | Review (max 2) | Done |
|-------|---------------------|----------------|------|
| task  | task                | task           | task |
| task  | task                |                | task |
| task  |                     |                |      |
```

**WIP Limit**: only a set number of items can be in each column at once.

### Advantage & Disadvantage

- **Advantage**: More relaxed, flexible, less ceremony
- **Disadvantage**: Harder to estimate/project delivery timelines (no sprints = no velocity)

### Which One is Best?

**There's no definitive answer.** It depends on your team's preference. The best process is the one you actually use.

---

## Buzzwords

| Term | Definition |
|---|---|
| **Scrum** | Most popular Agile framework — sprints, standups, retros |
| **Kanban** | Agile framework — continuous flow, no sprints, WIP limits |
| **Sprint** | Time-boxed work period, usually 2 weeks |
| **Sprint Planning** | Meeting to decide what goes into the sprint |
| **Sprint Backlog** | The subset of work selected for the current sprint |
| **Product Backlog** | The full prioritized list of all work to be done |
| **Ticket** | A unit of work in a project management tool |
| **Standup** | Daily 10-15 min sync meeting (standing up) |
| **Retrospective** | End-of-sprint meeting: what went well, what didn't, questions |
| **Time-boxing** | Constraining work to a fixed time period |

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: Agile](12-agile.md) | [Next: Waterfall ->](14-waterfall.md) |
