<div align="center">

<img src="assets/sentinel-logo.png" alt="SENTINEL Logo">

# S E N T I N E L

### TACTICAL INTELLIGENCE FOR EVE ONLINE

**Your Tactical Intelligence HQ for New Eden.**

### **Built to be the most capable tactical intelligence platform for EVE Online.**

<br>

**LIVE KILL MAP · UNIQUE TACTICAL LIVE MAP WARNING SYSTEM · MULTI-CHANNEL INTEL MAP**

<br>

![Status](https://img.shields.io/badge/STATUS-ACTIVE%20DEVELOPMENT-35c98b?style=flat-square)
![Channel](https://img.shields.io/badge/CHANNEL-ALPHA-4da3d9?style=flat-square)
![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS-737d8c?style=flat-square)
![Version](https://img.shields.io/badge/PUBLIC%20BUILD-0.2.29--alpha-8b6fd9?style=flat-square)

<br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

</div>

---

## ONE TACTICAL PICTURE OF NEW EDEN

**SENTINEL** is a Windows-based tactical intelligence and situational-awareness platform for **EVE Online**.

It is built for pilots who do not want to mentally combine a killboard, several Intel channels, a route planner, scout information and a universe map while something is already moving toward their pocket.

SENTINEL fuses **live kill activity, multiple Intel sources, scout context, monitoring position, jump distance, route context and native alerts** into one operational picture.

> **SENTINEL doesn't just show kills. It turns live events into actionable tactical intelligence.**

### **See the threat. Know the distance. Watch the route. React before it reaches you.**

---

# THE THREE CORE SYSTEMS

## 💀 LIVE KILL MAP

### **Live kill activity across New Eden — analyzed, mapped and configurable.**

Incoming live kill activity is resolved against SENTINEL's full New Eden universe graph and placed directly into tactical map context.

Instead of leaving a kill buried inside a scrolling feed, SENTINEL can show the pilot:

- **where** the event happened,
- **how many jumps away** it is from the active monitoring origin,
- **how fresh** the event is,
- **which ship / kill context** is relevant,
- and **how the system relates to the surrounding route and tactical situation**.

The Live Kill Map is designed to be configurable for different play styles. Tactical controls include configurable Kill ranges, marker lifetime, pulse / radar lifetime, visual threat colors and independent alert behavior.

Whether you are mining, hauling, scouting, roaming or watching a staging pocket, the important question is not only *what died?*

It is:

> **Where did it happen, how close is it, and does it matter to me right now?**

---

## 🚨 UNIQUE TACTICAL LIVE MAP WARNING SYSTEM

### **Your Overview tells you what's on grid. SENTINEL helps tell you what's coming.**

One of SENTINEL's defining systems is its **Unique Tactical Live Map Warning System**.

Live events are not treated as isolated feed entries. SENTINEL evaluates them around the pilot's selected tactical monitoring origin and can turn relevant activity into an active warning layer on the map.

The warning system combines:

- live map indicators,
- tactical pulses and radar-style persistence,
- configurable jump ranges,
- monitoring-origin awareness,
- route and system context,
- native Windows audio,
- separate Kill and Intel sound profiles,
- and threat-oriented visual presentation.

A hostile kill several jumps away should not require the pilot to constantly refresh another website and calculate the route mentally.

**SENTINEL puts the event on the map, gives it distance and context, and warns around the position you are actually monitoring.**

> **From raw kill events to tactical awareness.**

---

## 🛰️ MULTI-CHANNEL INTEL MAP

### **Multiple Intel channels. One map. One tactical picture.**

EVE Intel rarely lives in one clean place.

SENTINEL can discover local EVE chat-log channels and lets the user explicitly enable multiple Intel channels for monitoring. Incoming reports are parsed, resolved and associated with New Eden systems before becoming part of the tactical picture.

The Intel layer can understand context such as:

- solar systems,
- characters,
- multi-word and numeric character names,
- ship types,
- common Intel count notation,
- hostile / clear context,
- scout contacts,
- and system association.

Instead of trying to follow several chat windows and assemble the situation in your head, SENTINEL brings enabled Intel sources together with the same **map, distance and monitoring-origin context** used by the rest of the platform.

### **One map. Multiple intelligence sources. One tactical picture.**

---

# FROM EVENT TO WARNING

```text
LIVE KILL / INTEL EVENT
          ↓
SYSTEM & ENTITY RESOLUTION
          ↓
MONITORING-ORIGIN DISTANCE
          ↓
TACTICAL RELEVANCE
          ↓
LIVE MAP INDICATOR
          ↓
VISUAL + NATIVE AUDIO WARNING
          ↓
SYSTEM DOSSIER / ROUTE CONTEXT
```

That pipeline is the core SENTINEL idea: **information should reduce reaction time — not create more noise.**

---

# TACTICAL MONITORING ORIGIN

SENTINEL deliberately separates three things that many tools blur together:

1. **Actual MAIN character position**
2. **Map camera / map focus**
3. **Tactical monitoring origin**

This means a pilot can freely explore New Eden without silently changing the location used for tactical range and alert calculations.

### AUTO · MAIN

By default, SENTINEL follows the current solar system of the configured MAIN character and recalculates tactical relevance as the pilot moves.

### MANUAL Monitoring

A pilot can deliberately monitor another system — for example a mining pocket, moon operation, staging area, chokepoint or planned route — while the map remains free to move independently.

The active monitoring origin is used for Kill, Intel, Scout, Watchlist, Threat and native-audio range context.

---

# TACTICAL MAP & ROUTING CONTEXT

SENTINEL uses CCP universe data to build a full New Eden Stargate graph and tactical map environment.

Current map capabilities include:

- Full New Eden system graph
- Region → Constellation → System semantic detail
- Cursor-centered continuous deep zoom
- Interactive systems and persistent operational labels
- Security-status visualization
- Live tactical event markers
- Jump-distance calculations
- Route context
- System Dossiers
- MAIN / Scout / monitoring-origin context
- LOCAL / CONSTELLATION / REGION / NEW EDEN camera presets

The map is an **operational intelligence surface**, not merely a static universe viewer.

---

# LIVE INTELLIGENCE FEED

The Live Intelligence Feed acts as the event timeline behind the tactical map.

Events can include:

- live Kill activity,
- mining-ship losses,
- Intel reports,
- Scout contacts,
- Watchlist context,
- character intelligence,
- and threat changes.

Feed events and map context stay connected without forcing the map camera to jump every time new information arrives.

---

# SYSTEM DOSSIERS & THREAT CONTEXT

Selected systems expose tactical context and deliberate actions such as:

- open zKill,
- focus on map,
- show route,
- and set a manual monitoring origin.

Threat and risk indicators are designed as **transparent tactical context**, not as certainty.

---

# NATIVE WINDOWS COMMAND CENTER

SENTINEL runs as a dedicated Windows application rather than requiring a normal browser workflow.

### Windows integration

- Dedicated SENTINEL application window
- Embedded WebView interface
- Native system tray
- Background monitoring
- Native Windows tactical audio
- Single-instance behavior
- Clean restart / exit handling
- Dedicated local SENTINEL service
- Per-user Windows installer
- Persistent local runtime data

Closing the visible window does not have to mean losing tactical monitoring.

---

# CONFIGURABLE HUD & OPERATOR EXPERIENCE

SENTINEL is built as a tactical workstation, not a dashboard that forces one fixed layout on every display.

Current interface systems include:

- Dark / Light / OLED themes
- German / English UI
- Persistent **100 / 110 / 120% side-HUD scaling**
- Map rendering kept independent from HUD scaling
- Configurable Kill and Intel ranges
- Configurable tactical markers and persistence
- Custom threat colors
- Independent Kill / Intel audio profiles
- Tactical System Dossiers
- Persistent monitoring origin

---

# EVE ONLINE INTEGRATION

SENTINEL currently combines several EVE-facing systems, including:

- EVE Online SSO Authorization Code + PKCE
- ESI character and location monitoring
- MAIN and Scout character roles
- Local EVE chat-log monitoring
- R2Z2 / zKillboard live kill consumption
- CCP Static Data Export universe data
- Official EVE Image Service assets
- Local Scan workflow

SENTINEL does **not** automate gameplay input.

Its purpose is to make available tactical information easier to understand and act on.

---

# SECURE RELEASE DELIVERY

Public Windows builds are delivered through the dedicated **SENTINEL release channel**.

The current update path includes:

`Update detected`
→ `Installer downloaded`
→ `SHA-256 verified`
→ `SENTINEL closes safely`
→ `Installer runs`
→ `Update installed`
→ `SENTINEL restarts`

Updates are only installed after explicit user action, and downloaded installers must pass the expected integrity verification before execution.

---

# CURRENT DEVELOPMENT STATUS

| | |
|---|---|
| **Project** | SENTINEL // Tactical Intelligence |
| **Developer** | Robocapa |
| **Platform** | Windows x64 |
| **Channel** | Alpha / pre-release |
| **Latest public build** | `0.2.29-alpha` |
| **Development** | Active |
| **Source code** | Private |

Current development priorities include tactical intelligence, interface usability, reliability, security and release trust.

Public development history and Windows builds are published through the dedicated SENTINEL release repository.

### **→ [SENTINEL Releases & Development Log](https://github.com/Robocapa-eve/sentinel-releases)**

---

# THE SENTINEL PRINCIPLE

> **Information should reduce reaction time — not create more noise.**

A normal killboard can tell you that something died.

An Intel channel can tell you that somebody saw something.

A map can tell you where a system is.

A route planner can tell you how to get there.

### **SENTINEL is being built to connect those signals into one tactical situation.**

**See the threat. Know the distance. Watch the route. React before it reaches you.**

---

<div align="center">

### Developed & maintained by Robocapa

**SENTINEL // TACTICAL INTELLIGENCE**

**Your Tactical Intelligence HQ for New Eden.**

<br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

<br><br>

<sub>
SENTINEL is an independent third-party application for EVE Online and is not affiliated with or endorsed by CCP Games.<br>
EVE Online and related marks are property of CCP hf.
</sub>

</div>
