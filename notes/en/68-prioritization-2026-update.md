# 68 - Prioritization Frameworks: 2026 Update

## Gold Standard Frameworks (2026)

| Tier | Frameworks | Why |
|---|---|---|
| **Tier 1** | **RICE**, **Weighted Scoring**, **Opportunity Solution Trees** | Battle-tested, scalable, data-friendly |
| **Tier 2** | **WSJF/Cost of Delay**, **Value vs Effort 2x2**, **Outcome-Based** | Strong in specific contexts (SAFe, exec comms, OKR orgs) |
| **Tier 3** | **Kano**, **ICE**, **MoSCoW**, **BUC** | Excellent for specific use cases, not universal |
| **Emerging** | **AI-augmented scoring** | AI generates initial scores from customer data, humans review |

## Quantitative Frameworks

### RICE (Most Popular)
> **Score = (Reach × Impact × Confidence) / Effort**

| Factor | What it is | Scale |
|---|---|---|
| **Reach** | How many users affected per time period | Actual number |
| **Impact** | How much it moves the metric | 0.25 (minimal) to 3 (massive) |
| **Confidence** | How sure are you about these estimates | 50%-100% |
| **Effort** | Person-months to build | Actual estimate |

### ICE (Quick Version)
> **Score = Impact × Confidence × Ease** (each 1-10)

### Weighted Scoring (Custom)
Define your own factors + weights. Example:

| Factor | Weight | Feature A (score) | Feature A (weighted) |
|---|---|---|---|
| Revenue potential | 30% | 8 | 2.4 |
| User demand | 25% | 9 | 2.25 |
| Strategic alignment | 20% | 7 | 1.4 |
| Competitive pressure | 15% | 6 | 0.9 |
| Ease of implementation | 10% | 4 | 0.4 |
| **Total** | 100% | | **7.35** |

### WSJF / Cost of Delay
> **Priority = Cost of Delay / Job Duration**

Cost of Delay = User-Business Value + Time Criticality + Risk Reduction

Best for: SAFe / Lean Agile at enterprise scale.

## The "Buckets" Technique (Strategic Evaluation)

Evaluate initiatives across strategic dimensions:

| Bucket | What it measures | Weight |
|---|---|---|
| **Budget / Resources** | Can we afford this now? Do we have the team? | 15-20% |
| **Market Opportunity** | TAM potential, revenue upside, user demand | 25-30% |
| **Time-to-Market** | How fast can we ship? Is there a window? | 15-20% |
| **Competitive Pressure** | Are competitors shipping this? Risk of falling behind? | 15-20% |
| **Strategic Alignment** | Does it match vision, OKRs, north star metric? | 15-20% |

## Qualitative Frameworks

### Kano Model
Classify features by customer satisfaction impact:
- **Basic** (must-have) — absent = angry, present = neutral
- **Performance** — more = happier (linear)
- **Delighters** — unexpected joy, absent = no complaint
- **Indifferent** — nobody cares
- **Reverse** — some users actively don't want it

### Opportunity Solution Trees (Teresa Torres)
```
Desired Outcome
  └── Opportunity 1
  │     ├── Solution A → Experiment
  │     └── Solution B → Experiment
  └── Opportunity 2
        └── Solution C → Experiment
```

## The Hybrid Approach (Best Practice 2026)

1. **Discover** → Opportunity Solution Trees / Jobs-to-be-Done
2. **Score** → RICE or Weighted Scoring (AI-assisted)
3. **Validate** → Buckets technique for strategic alignment
4. **Communicate** → Value vs Effort 2x2 for executive buy-in
5. **Sequence** → WSJF / Cost of Delay for sprint ordering

## AI-Powered Prioritization Tools

| Tool | AI Features |
|---|---|
| **Productboard** | AI insight clustering from feedback, auto-suggests priority |
| **Airfocus** | AI Priority Poker, modular scoring, auto-weight suggestion |
| **Linear** | AI triage, auto-labeling, priority suggestions |
| **Notion AI** | Build-your-own prioritization with AI formulas |
| **ChatGPT / Claude** | Paste backlog, ask for RICE scoring — "prioritization co-pilot" |

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: Working with Executives](67-working-with-executives-and-stakeholders.md) | [Next: Preparing for a PM Job ->](69-preparing-for-pm-job.md) |
