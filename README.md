<div align="center">

<img src="assets/sentinel-logo.png" width="50" alt="SENTINEL mark">

# SENTINEL // TACTICAL INTELLIGENCE

### Tactical Intelligence for EVE Online

**Private development. Evidence first. Built for New Eden.**

`0.4.0-alpha` · `CLOSED DEVELOPMENT` · `WINDOWS x64`

**English** · [Deutsch](README_DE.md)

</div>

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> ROBOCAPA

I develop **SENTINEL**, an independent tactical-intelligence application for **EVE Online**.

The project is built around one principle:

> **Information should reduce reaction time — not create more noise.**

SENTINEL is not intended to be another static map or another killboard. The goal is a persistent tactical command surface that combines live public observations, New Eden context, user-supplied intelligence and bounded historical evidence without pretending that old data is current truth.

The project is currently in **closed private development**. Source code, release assets and active development remain private until the product is ready for deliberately granted access.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> CURRENT SIGNAL // 0.4.0-alpha

The active `0.4.0-alpha` line is the largest SENTINEL development cycle so far.

### MAP 2.0

One continuous New Eden command surface with semantic LOD, stable universe geometry, real Stargate topology, route/navigation context, Territory/SOV layers and deeper System/Pilot/Entity intelligence surfaces.

### OVERWATCH V2

A rebuilt current-session live-kill architecture designed around one accepted event stream for Feed, Map, Heat, Tactical Picture and Kill Bursts. Fresh process means fresh session; durable history does not silently become live truth.

### Tactical Intelligence

Evidence-backed analysis now spans Tactical Summary, D-Scan analysis, Watchlists 2.0, Combat Hot Zones, Route Risk / Safer Route, Compare Intelligence, pilot/system/entity context and bounded historical behavior patterns.

### Tactical Memory

Recent public combat observations can be retained in a bounded rolling 90-day historical Memory for recency-aware analysis, reconciliation and explainable intelligence.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DEVELOPMENT LINE

SENTINEL has moved through three important recent stages:

| Line | Meaning |
|---|---|
| `0.2.30-alpha` | last packaged Windows Tactical Intelligence build |
| `0.3.0-alpha` | frozen Live Relay / Tactical Memory / Intelligence Brain milestone |
| `0.4.0-alpha` | active MAP 2.0 / OVERWATCH V2 / Tactical Intelligence development |

The current phase also included a dedicated core cleanup: obsolete shadow/soak paths were retired, live authority semantics were consolidated, simulation was isolated from evidence, frontend transport/presentation responsibilities were separated and the release workflow was hardened around PR + CI + controlled promotion.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> TRUTH MODEL

SENTINEL follows:

**OBSERVED → INFERRED → CONFIDENCE**

That distinction matters in EVE intelligence:

- a published killmail proves the event, not continued pilot presence;
- historical fits are not current fits;
- repeated co-attacking is not automatically fleet membership;
- Local and D-Scan are snapshots, not permanent state;
- route, roam and behavior reconstruction must remain evidence- and recency-aware.

SENTINEL does not invent unsupported threat or attack probabilities.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> OPERATOR FOCUS

The application is being built for pilots and groups who want better context around:

- mining and industrial operations;
- hauling and route awareness;
- PvE pockets and staging systems;
- scouting and roaming;
- hunting and hostile activity discovery;
- corporation/fleet situational awareness.

The same product can help a pilot avoid activity or deliberately find it. SENTINEL provides context; the player makes the decision.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DATA BOUNDARY

SENTINEL is designed around legitimate third-party data sources and user-provided observations such as CCP ESI/SDE, public combat publication data, Local/D-Scan clipboard snapshots and configured Intel-channel/log evidence.

It does **not** automate gameplay input, broadcast client actions or manipulate the EVE client.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> RELEASE PHILOSOPHY

Development moves quickly, releases deliberately.

```text
Feature / Fix / Chore
→ Pull Request
→ Full CI
→ Stable Development Foundation
→ Acceptance + Live QA
→ Release Candidate
→ Verified Windows Build
→ Access Decision
```

The project remains private until that final access decision is intentional.

---

<div align="center">

<img src="assets/sentinel-logo.png" width="28" alt="SENTINEL mark">

### KEEP YOUR TOOLS. ADD INTELLIGENCE.

**See the event. Know the distance. Understand the evidence. React sooner.**

<sub>SENTINEL is an independent third-party application for EVE Online and is not affiliated with or endorsed by CCP Games. EVE Online and related marks are property of CCP hf.</sub>

<br><br>

**Developed & maintained by Robocapa**

</div>
