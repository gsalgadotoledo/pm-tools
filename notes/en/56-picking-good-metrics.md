# 56 - Picking Good Metrics

## Metrics Roll Up

Your team metric feeds into the company-level metric:

```
Company goal: Increase time spent on Facebook
    ↓
Your team: Increase comments/person by 5%
    (because people who comment more stay longer)
```

You may not track the top-level metric directly — you track what **drives** it.

## Exploratory vs Reporting Metrics

| | Exploratory | Reporting |
|---|---|---|
| **Purpose** | Hunt for clues, investigate behavior | Track product health over time |
| **Duration** | Ad-hoc, temporary | Long-term, consistent |
| **Audience** | You and your team | Boss, investors, the company |
| **Example** | How many people click button X on page Y | Monthly Active Users, retention rate |

## What Makes a Good Metric?

### 1. Understandable
- Explain it by just saying its name
- Usually: something ÷ something = percentage, or count of X per user
- NOT: "people who clicked button A twice then went back and clicked B"

### 2. A Rate or Ratio (not a raw number)
| Bad metric | Good metric | Why |
|---|---|---|
| Total users ever | Monthly Active Users (MAU) | Raw total always goes up — hides problems |
| Total nights booked (Airbnb) | Avg nights booked/person/month | Raw total affected by marketing, economy, etc. |

### 3. Not Based on False Correlation
> Ice cream sales and drowning deaths both go up in summer — doesn't mean ice cream causes drowning.

Make sure your metrics actually **impact each other**, not just track together by coincidence.

### 4. Changeable by Your Team
Pick metrics your product changes can actually move.

| Scenario | Bad metric | Better metric |
|---|---|---|
| Users only have 2 hrs/day available | Time spent in app (capped) | Logins per week, sessions per week |
| E-commerce: users buy 1x/month | Purchases per month (stuck at 1) | Avg order value per visit |

## Summary Checklist

- [ ] Can anyone understand it from the name?
- [ ] Is it a rate/ratio, not a raw number?
- [ ] Are we sure the correlation is causal, not coincidental?
- [ ] Can our team's work actually change this metric?

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: Metrics Categories](55-metrics-categories.md) | Next: ... -> |
