# 46 - MVP Types (Part 3): Concierge, Piecemeal, Wizard of Oz

## 6. Concierge MVP

**Manually** help users accomplish the task your product would do.

| Aspect | Detail |
|---|---|
| **How** | Offer a "beta program" to a small group, then personally walk them through the task |
| **Why** | See firsthand if what you're building is helpful and necessary |
| **Example: Amazon bot** | Instead of building an algorithm, email power users personalized recommendations manually |
| **Example: Rent the Runway** | Physically helped women on college campuses pick, stock, organize, and return fancy dresses before building the platform |

---

## 7. Piecemeal MVP

Piece together **existing off-the-shelf tools** to simulate your product.

| Tool | What it does |
|---|---|
| Weebly / Wix / Squarespace | Create pages, take orders |
| Formstack / Typeform / Jotform | Advanced forms and calculations |
| Twilio | Send text messages, build SMS systems |
| Recurly | Manage subscriptions |
| WordPress | Full site with plugins |

**Example: Groupon** (originally "The Point")
- Site built on **WordPress**
- Orders triggered emails via **Apple Mail + AppleScript**
- AppleScript auto-generated coupons and sent them back
- No complex backend needed

---

## 8. Wizard of Oz MVP

Front-end looks **fully functional**, but a human is manually doing everything behind the scenes.

```
User sees:    Beautiful working app
Reality:      Person behind a curtain fulfilling requests manually
```

| Aspect | Detail |
|---|---|
| **Why** | The biggest dev effort is server-side logic nobody sees — skip it |
| **How** | Build a real-looking front-end, have someone manually fulfill on the backend |
| **Example** | Social network "Match Me" button — someone manually reviews profiles and emails matches |
| **Classic Example: Zappos** | Online shoe store, no inventory. When someone ordered, they walked across the street, bought the shoes, and shipped them |

---

## Complete MVP Types Summary

| # | Type | Effort | What's fake | Example |
|---|---|---|---|---|
| 1 | **Email** | Lowest | Everything | AppSumo |
| 2 | **Shadow Button** | Low | The feature | Login button tests |
| 3 | **404 / Coming Soon** | Low-Med | The product page | Amazon, Oculus Rift |
| 4 | **Explainer Video** | Medium | The demo | Dropbox |
| 5 | **Landing Page** | Medium | The product | Buffer, Basecamp |
| 6 | **Concierge** | Medium | Automation (manual labor) | Rent the Runway |
| 7 | **Piecemeal** | Medium | Custom development | Groupon (WordPress + AppleScript) |
| 8 | **Wizard of Oz** | Med-High | Backend/server logic | Zappos |

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: MVP Types Part 2](45-mvp-types-part2.md) | Next: ... -> |
