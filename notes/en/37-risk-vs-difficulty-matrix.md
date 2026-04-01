# 37 - Risk vs Difficulty Matrix

## Two Criteria for Prioritizing Assumptions

| Criteria | Meaning |
|---|---|
| **Risk** | How risky is this assumption to the product? Can it sink the ship or just change course? |
| **Difficulty** | How hard is it to test this assumption? How much effort/resources needed? |

## The Matrix

```
        Risk
  High  |  3. Do after   |  1. DO FIRST
        |  high-risk     |  ← Best bang
        |  low-diff      |     for buck
        |----------------|----------------
  Low   |  4. IGNORE     |  2. Quick wins
        |  not worth it  |  cross t's
        |                |  dot i's
        +--------------------------------
              High              Low
                    Difficulty
```

## Priority Order

| Priority | Quadrant | Why |
|---|---|---|
| **1st** | High Risk, Low Difficulty | Most meaningful progress with least effort |
| **2nd** | High Risk, High Difficulty | Now you're confident — can ask for bigger team commitments |
| **3rd** | Low Risk, Low Difficulty | Quick wins — cross your t's and dot your i's |
| **4th (skip)** | Low Risk, High Difficulty | Probably not worth focusing on at all |

## Example: Subscription Gifts for Airbnb Hosts

| Assumption | Risk | Difficulty | Quadrant |
|---|---|---|---|
| Guests don't want gifts from hosts | **High** (kills the whole idea) | **Low** (just ask a few guests or test with one host) | **Do first** |
| Hosts won't buy items they can get locally | **Low** (not a deal-breaker) | **High** (need to build a site, stock items, observe) | **Ignore** |

## Entrepreneur vs PM

| | Entrepreneur | Product Manager |
|---|---|---|
| **Focus** | Always tackle riskiest assumption first | Balance risk with difficulty — resources are shared |
| **Why** | You ARE the organization | You don't drive singular focus — team time is rationed |

---

## My Notes

-

---

| | |
|---|---|
| [<- Previous: Ranking Risky Assumptions](36-ranking-risky-assumptions.md) | Next: ... -> |
