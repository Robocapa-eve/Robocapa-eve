<div align="center">

<img src="assets/sentinel-logo.png" width="54" alt="SENTINEL mark">

# SENTINEL // TACTICAL INTELLIGENCE

### A live intelligence system for EVE Online

**Live kills in range. Intel-channel activity on the map. Pilot intelligence underneath.**

`0.4.0-alpha` · `CLOSED DEVELOPMENT` · `WINDOWS x64`

**English** · [Deutsch](README_DE.md)

</div>

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> ROBOCAPA // ENGINEERING NEW EDEN INTELLIGENCE

I develop **SENTINEL**, an independent tactical-intelligence platform for **EVE Online**.

What started as a practical question — *can I see relevant kills and Intel reports around me directly on a live map?* — has grown into a much larger system.

Today, the map is only the visible surface.

SENTINEL receives live public combat observations and explicitly configured Intel-channel evidence, places them into real New Eden topology and then correlates those signals against the tactical evidence already available to the system.

For every observed pilot, corporation, alliance and system with sufficient evidence, SENTINEL can expose context such as:

- activity windows and recurring systems;
- observed hull and weapon usage;
- historical fitting families;
- recurring co-attackers and gang tendencies;
- roaming/corridor evidence and movement episodes;
- target preferences and behavior patterns;
- current route exposure and safer-route context;
- system, corporation and alliance activity baselines;
- live events viewed against bounded Tactical Memory.

> **The live event is only the beginning. SENTINEL tries to explain the tactical picture behind it.**

Historical evidence is never silently presented as current truth. A historical fit is not a current fit. A reconstructed corridor is not a proven travel path. Recurring co-attackers are not automatically fleet members.

That distinction is part of the product, not a disclaimer bolted on afterwards.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> LIVE MAP // THE FRONT LINE

### LIVE KILLS IN RANGE

Accepted current-session public combat events appear in the tactical map context around the operator. The same accepted event IDs feed Map, Live Feed, Heat, Tactical Picture and Kill Bursts.

### INTEL CHANNEL LIVE MAP

Explicitly configured EVE Intel channels are monitored locally, deduplicated across multibox logs and projected into the same tactical map and Live Intelligence Feed with a separate operator-controlled Intel Range.

### ONE OPERATING PICTURE

Local snapshots, D-Scan, Scouts, Watchlists, public kills and Intel reports are not treated as isolated widgets. They converge into one live command surface.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> INTELLIGENCE ENGINE // WHAT RUNS UNDERNEATH

The `0.4.0-alpha` line pushes SENTINEL beyond a live-map tool into a persistent intelligence layer.

New observations can be correlated with bounded recent evidence to build Pilot, System, Corporation and Alliance intelligence, including Tactical Summary, D-Scan analysis, Watchlists 2.0, Combat Hot Zones, Route Risk / Safer Route, Compare Intelligence, Hunter Trails, recurring aggressor networks and evidence-backed behavior context.

The operating principle is simple:

**OBSERVED → INFERRED → CONFIDENCE**

SENTINEL does not invent unsupported threat or attack probabilities and does not claim information its data sources cannot provide.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> CURRENT DEVELOPMENT // 0.4.0-alpha

**MAP 2.0** — one continuous New Eden command surface with semantic LOD, real Stargate topology, navigation/route context, SOV/Territory layers and deep Pilot/System/Entity surfaces.

**OVERWATCH V2** — dedicated current-session live-kill architecture across Feed, Map, Heat, Tactical Picture and Kill Bursts, with fresh-process session truth and bounded fallback behavior.

**Tactical Memory** — a rolling 90-day PostgreSQL-backed history of recent public combat observations with provenance, reconciliation and read-only intelligence consumers.

**Tactical Intelligence** — evidence-backed analysis of pilots, systems, corporations, alliances, route pressure, roaming patterns, gang tendencies and historical fit evidence.

The project remains in **closed private development** until access is deliberately granted.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DEVELOPMENT LINE

| Line | Meaning |
|---|---|
| `0.2.30-alpha` | last packaged Windows Tactical Intelligence build |
| `0.3.0-alpha` | frozen Live Relay / Tactical Memory / Intelligence Brain milestone |
| `0.4.0-alpha` | active MAP 2.0 / OVERWATCH V2 / Tactical Intelligence development |

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

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DATA BOUNDARY

SENTINEL is designed around legitimate EVE third-party data boundaries: CCP ESI/SDE, public combat publication evidence, explicit Local/D-Scan clipboard snapshots and explicitly configured Intel-channel/log observations.

It does **not** automate gameplay input, broadcast client actions or manipulate the EVE client.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> PROJECT HOME

**Robocapa-eve on GitHub:** https://github.com/Robocapa-eve

SENTINEL source development and the private release vault are maintained under this account while the project remains closed.

---

<div align="center">

<img src="assets/sentinel-logo.png" width="30" alt="SENTINEL mark">

### KEEP YOUR TOOLS. ADD INTELLIGENCE.

**Live signal in. Tactical context out.**

**See the event. Know the distance. Understand the pilots behind it. React sooner.**

<sub>SENTINEL is an independent third-party application for EVE Online and is not affiliated with or endorsed by CCP Games. EVE Online and related marks are property of CCP hf.</sub>

<br><br>

**Developed & maintained by Robocapa**

</div>
