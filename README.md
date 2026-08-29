<div align="center">

<img src="assets/sentinel-logo.png" alt="SENTINEL Logo">

# S E N T I N E L

### TACTICAL INTELLIGENCE FOR EVE ONLINE

**Real-time tactical situational awareness, highly specialized live feed intelligence monitoring and map-based threat analysis for New Eden.**

<br>

![Status](https://img.shields.io/badge/STATUS-ACTIVE%20DEVELOPMENT-35c98b?style=flat-square)
![Channel](https://img.shields.io/badge/CHANNEL-ALPHA-4da3d9?style=flat-square)
![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS-737d8c?style=flat-square)
![Version](https://img.shields.io/badge/VERSION-0.2.29--alpha-8b6fd9?style=flat-square)

<br><br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

</div>

---

## SENTINEL

**SENTINEL** is a tactical intelligence and situational awareness application developed for **EVE Online**.

Designed for pilots who want relevant information immediately available without unnecessary clutter, SENTINEL combines live intelligence, kill activity, character monitoring, system awareness and tactical map data in a focused Windows environment.

The goal is simple:

> **See what matters. Know what is happening. React before it becomes a problem.**

### Core Systems

- **Live Tactical Map**
- **Full New Eden Navigation Data**
- **Semantic Deep-Zoom Map**
- **EVE Online SSO & ESI Integration**
- **Real-time Kill Intelligence**
- **zKillboard / R2Z2 Live Kill Feed**
- **Intel Channel Monitoring**
- **Multi-word EVE Character Resolution**
- **System Threat Assessment**
- **Character & Scout Tracking**
- **Automatic MAIN Character Tracking**
- **Manual Tactical Monitoring Origin**
- **Configurable Kill & Intel Ranges**
- **System Dossiers & Tactical Context**
- **Persistent Tactical Live Feed**
- **Native Windows Alert System**
- **Independent Kill & Intel Audio Profiles**
- **Windows System Tray Integration**
- **Dedicated SENTINEL Windows Client**
- **Secure One-Click Update System**
- **SHA-256 Release Verification**
- **Automatic Restart After Updates**

---

## Tactical Monitoring

SENTINEL separates the **map focus** from the actual **tactical monitoring center**.

This allows pilots to freely explore New Eden without accidentally changing the system used for tactical range calculations.

### AUTO · MAIN

By default, SENTINEL follows the current solar system of the configured **MAIN** character.

When the pilot moves through New Eden, SENTINEL automatically updates the monitoring origin and recalculates tactical information from the new location.

This affects:

- Kill distances
- Intel distances
- Scout contacts
- Watchlist information
- Threat assessment
- Native audio alerts

### MANUAL Monitoring

Any solar system can also be selected as a dedicated tactical monitoring origin.

This allows a pilot to monitor another system, mining area, staging location, travel route or strategic chokepoint while remaining somewhere else in New Eden.

Returning to **MAIN Follow** immediately restores automatic tracking of the active MAIN character.

---

## Tactical Map

The SENTINEL tactical map is designed as an operational intelligence tool rather than a traditional static universe map.

### Map Features

- Cursor-centered continuous zoom
- Deep tactical system-level zoom
- Region → Constellation → System semantic detail
- Persistent system labels at operational zoom levels
- Interactive system selection
- System search
- System dossiers
- Jump-distance visualization
- Security-status visualization
- Tactical event markers
- Threat context
- Navigation and route information
- Automatic MAIN location tracking
- Manual monitoring origin selection

Exploring or focusing a system on the map does **not** change the active tactical monitoring origin unless the pilot explicitly selects **Monitor / Überwachen**.

---

## Live Intelligence

SENTINEL combines multiple intelligence sources into a single tactical view.

Information can include:

- Ship kills
- Mining ship losses
- Intel channel reports
- Scout contacts
- Character intelligence
- Watchlist activity
- Character movement
- Current MAIN location
- Tactical threat changes

Intel events are normalized, resolved and correlated with New Eden system data before being displayed.

The Live Intelligence Feed is designed to surface relevant events without mixing internal SENTINEL location telemetry with actual tactical intelligence.

---

## Intel Channel Monitoring

SENTINEL can monitor selected local EVE Online chat logs and interpret tactical reports in real time.

The intelligence parser supports:

- Solar system detection
- Multi-word EVE character names
- Numeric character name components
- Intel count filtering
- Character resolution
- Tactical system association
- Scout and hostile contact classification

Only channels explicitly enabled by the user are processed.

---

## Native Windows Application

SENTINEL runs as a dedicated Windows application rather than requiring a normal browser workflow.

### Windows Integration

- Dedicated SENTINEL application window
- Native system tray integration
- Background operation
- Native Windows alert audio
- Dedicated local SENTINEL service
- Automatic startup update checks
- Clean restart handling
- Standalone Windows installer
- Separate application and runtime data

Runtime configuration is stored separately from the installed application files so updates can replace SENTINEL without destroying local settings.

---

## Alert System

SENTINEL provides native Windows alert audio designed to remain functional while EVE Online is in the foreground.

Kill and Intel alerts can use independent sound profiles.

### Available Alert Profiles

- **Sentinel Pulse**
- **Command Alert**
- **Scanner Ping**
- **Deep Warning**

Alert ranges are directly tied to the configured tactical monitoring radius.

This means the selected monitoring origin determines which kill, Intel and tactical events are considered relevant.

---

## Secure One-Click Updates

SENTINEL includes its own secure public release and update infrastructure.

At startup, SENTINEL automatically checks the public release channel for newer versions.

When no newer version is available, SENTINEL confirms that the installed version is current.

When a newer release is available, the user can start the update directly from SENTINEL.

### Update Workflow

`Update detected`
→ `Installer downloaded`
→ `SHA-256 verified`
→ `SENTINEL closes safely`
→ `Installer runs`
→ `Update installed`
→ `SENTINEL restarts automatically`

The installer is never executed before its SHA-256 checksum matches the value published by the SENTINEL release infrastructure.

Updates are never installed without explicit user action.

### Update Validation

The complete real-world update path has been successfully tested:

**SENTINEL 0.2.28-alpha → SENTINEL 0.2.29-alpha**

including:

- Public release detection
- Update notification
- Installer download
- SHA-256 verification
- Installation
- Automatic shutdown
- Automatic restart
- Post-update version verification

---

## Development Status

SENTINEL is currently under **active alpha development**.

**Current release channel:** `ALPHA`

**Current version:** `0.2.29-alpha`

The project is being developed with a strong focus on:

`Reliability` · `Clarity` · `Performance` · `Operational Awareness` · `Security`

Public alpha releases and secure in-app updates are now available.

Documentation will continue to expand as SENTINEL progresses toward broader public testing.

---

## Project Structure

| Resource | Status |
|---|---|
| SENTINEL Application | 🟢 Active Development |
| Windows Client | 🟢 Active Development |
| Tactical Intelligence | 🟢 Operational |
| Tactical Map | 🟢 Operational |
| Public Alpha Releases | 🟢 Active |
| Automatic Updates | 🟢 Operational |
| SHA-256 Release Verification | 🟢 Operational |
| Documentation | 🟡 In Preparation |
| EVE Community Listing | ⚪ Future Release Goal |

---

## Current Milestone

### SENTINEL 0.2.29-alpha

The current development milestone introduces the complete SENTINEL update infrastructure while building on the tactical monitoring and mapping systems introduced in previous alpha releases.

### Highlights

- Secure public release discovery
- Automatic update checks on startup
- German and English update notifications
- Manual update checks
- One-click installer download
- SHA-256 verification
- Automated update installation
- Automatic SENTINEL restart
- Automatic MAIN character monitoring
- Manual tactical monitoring origins
- Cursor-centered semantic New Eden zoom
- Deep tactical map detail
- Persistent system labels
- System dossier improvements
- Improved Live Intelligence Feed handling
- Improved EVE character name parsing

---

## Development Philosophy

SENTINEL is built around a simple principle:

> **Information should reduce reaction time — not create more noise.**

Features are therefore designed around practical use while actively playing EVE Online:

- Important information first
- Minimal unnecessary interaction
- Clear tactical context
- Deliberate alerts instead of constant noise
- Predictable controls
- Reliable background operation
- Secure update handling

---

<div align="center">

### Developed & maintained by Robocapa

**SENTINEL · Tactical Intelligence**

*See what matters. Know what is happening.*

<br>

**🇬🇧 English** · [🇩🇪 Deutsch](README_DE.md)

<br><br>

<sub>
SENTINEL is a third-party application for EVE Online and is not affiliated with or endorsed by CCP Games.<br>
EVE Online and all related trademarks are the property of CCP hf.
</sub>

</div>
