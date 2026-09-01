<div align="center">

<img src="assets/sentinel-logo.png" width="44" alt="SENTINEL Logo">

# SENTINEL // TACTICAL INTELLIGENCE

### **Tactical Intelligence for EVE Online**

**Your Tactical Intelligence HQ for New Eden.**

<br>

![Status](https://img.shields.io/badge/STATUS-ACTIVE%20DEVELOPMENT-35c98b?style=flat-square)
![Channel](https://img.shields.io/badge/CHANNEL-ALPHA-4da3d9?style=flat-square)
![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS-737d8c?style=flat-square)
![Public](https://img.shields.io/badge/PUBLIC%20BUILD-0.2.30--alpha-8b6fd9?style=flat-square)
![Development](https://img.shields.io/badge/DEV%20LINE-0.3.0--alpha-d86f45?style=flat-square)

<br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

</div>

<p align="center">
  <a href="https://raw.githubusercontent.com/Robocapa-eve/sentinel-releases/main/assets/screenshots/sentinel-tactical-intelligence-overview-full.jpg">
    <img src="https://raw.githubusercontent.com/Robocapa-eve/sentinel-releases/main/assets/screenshots/sentinel-tactical-intelligence-overview.webp" width="460" alt="SENTINEL Tactical Intelligence Overview">
  </a>
</p>

---

## 👋 Robocapa

I am the developer behind **SENTINEL**, an independent tactical-intelligence platform for **EVE Online**.

The project is built around one rule:

> **Information should reduce reaction time — not create more noise.**

SENTINEL combines live events from New Eden with map context, monitoring origin, jump distance, Intel channels, Scouts, Local Scan, route context and Windows alerts.

The current development line is now adding something deeper behind that interface: **bounded Tactical Memory and an explainable Intelligence Brain**.

### **See the threat. Know the distance. Understand the pattern. React sooner.**

---

# ⚡ LATEST SENTINEL ENGINEERING SPRINT

### **31 August → 1 September 2026**

Two calendar days produced the largest architecture jump in SENTINEL so far.

The sprint started with the public `0.2.30-alpha` Tactical Intelligence System and continued into a production-backed `0.3.0-alpha` intelligence foundation:

- 🛰️ dedicated HTTPS/WSS Live Relay
- 🧠 PostgreSQL 16-backed Tactical Memory
- 🔄 completed-day reconciliation and safe missing-ID repair
- 📦 **13,962 public killmails** durably processed by a bounded historical production canary
- 🕒 rolling **90-day UTC** Memory retention
- 🛡️ verified PostgreSQL backup and disposable restore drills
- 🧠 Tactical Intelligence Brain **1A** for observed pilot behavior
- 🧠 Tactical Intelligence Brain **1B** for systems, corporations and alliances
- 🔐 hardened security, CI and repository-integrity automation

The final combined Windows/relay repository gate completed with **224 tests passed** on Windows / Python 3.12. The dedicated PostgreSQL-backed Tactical Intelligence 1B line passed **71 tests**.

At the latest 1B production checkpoint, the bounded Memory contained roughly **480k canonical kills**, **2.0M attacker rows** and **7.8M item rows**.

### → [Read the full public engineering chronicle](https://github.com/Robocapa-eve/sentinel-releases/blob/main/CHANGELOG.md)

`0.3.0-alpha` remains a development line. The downloadable Windows build deliberately remains `0.2.30-alpha` until a real 0.3.0 installer has been built, tested, published and verified.

---

# 🛰️ WHAT SENTINEL IS BECOMING

SENTINEL is not another static map and not another killboard.

It is being built as a persistent tactical companion for pilots who want to understand:

- what is happening now
- how far away it is
- whether it matters to their operation
- whether recent behavior shows a useful pattern

The same intelligence can protect a mining operation, hauling route, PvE pocket or staging system — or help hunters, scouts and roamers find active space.

**Built for miners, haulers, PvE pilots, explorers, scouts, hunters, roamers, fleets and corporations.**

---

# ⚡ CURRENT OPERATOR SYSTEMS

### 💀 LIVE KILL MAP
Public kill activity is resolved against the New Eden universe graph and placed into map/distance context.

### 🚨 TACTICAL LIVE MAP WARNING SYSTEM
Relevant activity becomes an active warning layer around the system actually being monitored.

### 🛰️ MULTI-CHANNEL INTEL MAP
User-enabled Intel channels feed into the same tactical map and monitoring context.

### 🧭 MONITORING ORIGIN
AUTO · MAIN can follow the configured MAIN character; MANUAL monitoring can watch another system while the map is explored independently.

### 📍 SYSTEM TOOLTIPS & ROUTE CONTEXT
Systems expose tactical history and deliberate map/route actions without forcing camera movement.

---

# 🧠 0.3.0 DEVELOPMENT LINE

The biggest recent change is behind the UI.

## Dedicated Live Relay

SENTINEL now operates a dedicated HTTPS/WSS relay at `relay.sentinel-eve.de` with sequential public R2Z2 ingestion, reconnect/resume and bounded live delivery.

Direct R2Z2 still remains the authoritative desktop source while the relay is validated as a future candidate path.

## Rolling 90-day Tactical Memory

Recent public combat observations can now be kept in a bounded PostgreSQL-backed Memory.

The production horizon is deliberately **90 days** so SENTINEL can learn recent tactical patterns without becoming an expensive permanent archive.

## Tactical Intelligence Brain 1A

Pilot behavior analysis can derive observed:

- ship and weapon usage
- target preferences
- recurring co-attacker relationships
- historical loss-fit families
- evidence, recency and confidence

## Tactical Intelligence Brain 1B

The Brain now also builds recent profiles for:

- solar systems
- corporations
- alliances
- attacker/victim hull patterns
- UTC activity distributions
- recurring co-attacking organizations

SENTINEL keeps inference honest: historical fits are not called current fits, recurring co-attackers are not automatically called fleet members, and route/roam reconstruction is still a future dedicated phase.

---

# 🖥️ WINDOWS APPLICATION

The current public build already includes:

- MAP INTEL profiles
- Tactical Feed Depth
- Tactical Intelligence Feed
- KILL HEAT
- Tactical Picture
- pinned System Tooltips
- SYSTEM VERLAUF
- Local Scan
- MAIN / Scout roles
- EVE SSO / ESI
- native Windows alerts
- Dark / Light / OLED themes
- German and English UI
- verified one-click updates

SENTINEL supports gameplay decisions and **does not automate gameplay input**.

---

# 🚀 PROJECT STATUS

| | |
|---|---|
| **Project** | SENTINEL // Tactical Intelligence |
| **Developer** | Robocapa |
| **Latest public Windows build** | `0.2.30-alpha` |
| **Current development line** | `0.3.0-alpha` |
| **Channel** | Alpha / pre-release |
| **Platform** | Windows x64 |
| **Source code** | Private |

### → [SENTINEL Releases](https://github.com/Robocapa-eve/sentinel-releases/releases)
### → [Public Development Log](https://github.com/Robocapa-eve/sentinel-releases/blob/main/CHANGELOG.md)
### → [Public Release Repository](https://github.com/Robocapa-eve/sentinel-releases)

The public updater remains on **0.2.30-alpha** until a real 0.3.0 Windows installer exists and has been verified.

---

# 🔭 NEXT DIRECTION

Current development is moving toward:

- UI integration for the 90-day Tactical Memory
- Pilot / System / Corporation / Alliance intelligence views
- Roam and movement episode inference with explicit confidence
- likely route reconstruction
- Content Hotspots / Hostile Pressure / Route Threat
- Watchlist and ganker-group intelligence
- broader public alpha testing

The project also follows a **GitHub zero-cost policy** for infrastructure: production tactical database storage is not designed around paid GitHub Artifacts, Packages or Codespaces.

---

<div align="center">

### **KEEP YOUR TOOLS. ADD INTELLIGENCE.**

**Protect yourself. Find the action. Understand what is happening beyond your grid.**

<br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

<br><br>

<sub>
SENTINEL is an independent third-party application for EVE Online and is not affiliated with or endorsed by CCP Games.<br>
EVE Online and related marks are property of CCP hf.
</sub>

<br>

**Developed & maintained by Robocapa**

</div>
