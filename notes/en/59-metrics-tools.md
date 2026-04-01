# 59 - Metrics Tools

## Analytics & Tracking Tools

| Tool | What it does | Best for | Cost |
|---|---|---|---|
| **Google Analytics** | Web + mobile tracking, traffic, user behavior | Everyone — start here | Free |
| **Crazy Egg** | Click data, heat maps, scroll maps, mouse movement | Understanding where users click and look on your site | Paid |
| **KISSmetrics** | Custom metrics, calculations, graphs, web + mobile | Deep analytics with custom metric setup | Expensive |
| **Mixpanel** | Individual user behavior, web + mobile, email/push integration | User-level analytics + retention campaigns | Expensive |
| **Optimizely** | A/B testing + click tracking | Testing which version performs better | Freemium |

## The Hub: Segment

**Problem**: Every analytics tool requires code on your site. Switching tools = switching code + losing historical data.

**Solution**: Segment is a **metrics hub**.

```
Your App/Website → Segment → Google Analytics
                           → Mixpanel
                           → KISSmetrics
                           → Any other tool
```

- Connect your app to Segment **once**
- Plug/unplug any analytics tool without changing your code
- Keeps a backup of your data
- Try out tools without losing history

> Set up Segment **first**, then try different analytics tools through it.

---

> **See [Tools 2026 Update](tools-2026-update.md#analytics--metrics-tools-2026-update)** — KISSmetrics faded, Amplitude/PostHog are the new leaders, Microsoft Clarity offers free heatmaps, and every tool now has AI-powered querying.

## My Notes

-

---

| | |
|---|---|
| [<- Previous: AARRR Pirate Metrics](58-aarrr-pirate-metrics.md) | Next: ... -> |
