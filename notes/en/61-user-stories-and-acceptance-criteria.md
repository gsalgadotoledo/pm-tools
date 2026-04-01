# 61 - User Stories & Acceptance Criteria

## User Story Format

> **As a** [type of user], **I want to** [action], **so that** [benefit].

| Part | What it is | Example |
|---|---|---|
| **As a** | Who | As a user |
| **I want to** | What (the action) | send pictures in a direct message |
| **So that** | Why (the benefit) | I can share my favorite photos with friends |

### Why This Format?

- PM writes the **what** and **why**, NOT the how
- Avoids telling engineers how to do their jobs
- Keeps focus on user value, not technical implementation

## Acceptance Criteria Format

> **Given** [context], **when** [action], **then** [expected result].

### Example

1. *Given I am a user and I click the add picture button in DM, I am presented with a pop-up to choose a file, I can upload it, and see a preview.*
2. *Given I have uploaded a photo, when I click send, the image is sent through DM and appears in the chat.*

### Why Acceptance Criteria?

- Very specific on how a feature should **function**
- Provides testable conditions → PM tests before release
- Engineers love specificity → helps them think through implementation

## Where They Live

```
Project Management Tool (Jira, etc.)
  └── Epic
       └── Ticket (card)
            ├── User Story
            ├── Acceptance Criteria
            └── Wireframes/Designs
```

## The Workflow

```
Backlog (stuff to do later)
  → Sprint Planning (pick items for next sprint)
    → Sprint (To Do → In Progress → QA/Testing → Done)
      → PM tests acceptance criteria
        → Approved → Released
```

## Real-Life in Jira

- **Backlog**: holds all planned work
- **Epics**: visible on the left sidebar, contain related tickets
- **Sprint**: drag tickets from backlog into the sprint
- **Board**: To Do → In Progress → Done (some add QA column)
- **Ticket detail**: user story + acceptance criteria + wireframes + comments

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: Vision to Epics](60-vision-to-epics-hierarchy.md) | [Next: Estimation & Velocity ->](62-estimation-and-velocity.md) |
