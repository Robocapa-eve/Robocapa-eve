<div align="center">

<img src="assets/sentinel-logo.png" width="44" alt="SENTINEL Logo">

# SENTINEL // TACTICAL INTELLIGENCE

### **Tactical Intelligence für EVE Online**

**Deine Tactical Intelligence Zentrale für New Eden.**

<br>

![Status](https://img.shields.io/badge/STATUS-AKTIVE%20ENTWICKLUNG-35c98b?style=flat-square)
![Kanal](https://img.shields.io/badge/KANAL-ALPHA-4da3d9?style=flat-square)
![Plattform](https://img.shields.io/badge/PLATTFORM-WINDOWS-737d8c?style=flat-square)
![Public](https://img.shields.io/badge/PUBLIC%20BUILD-0.2.30--alpha-8b6fd9?style=flat-square)
![Development](https://img.shields.io/badge/DEV%20LINE-0.3.0--alpha-d86f45?style=flat-square)

<br>

[🇬🇧 English](README.md) · **🇩🇪 Deutsch**

</div>

<p align="center">
  <a href="https://raw.githubusercontent.com/Robocapa-eve/sentinel-releases/main/assets/screenshots/sentinel-tactical-intelligence-overview-full.jpg">
    <img src="https://raw.githubusercontent.com/Robocapa-eve/sentinel-releases/main/assets/screenshots/sentinel-tactical-intelligence-overview.webp" width="460" alt="SENTINEL Tactical-Intelligence-Übersicht">
  </a>
</p>

---

## 👋 Robocapa

Ich bin der Entwickler hinter **SENTINEL**, einer unabhängigen Tactical-Intelligence-Plattform für **EVE Online**.

Das Projekt folgt einer einfachen Regel:

> **Informationen sollen die Reaktionszeit verkürzen – nicht zusätzlichen Lärm erzeugen.**

SENTINEL verbindet Live-Ereignisse aus New Eden mit Map-Kontext, Monitoring Origin, Jump-Distanzen, Intel-Channels, Scouts, Local Scan, Route-Kontext und nativen Windows-Warnungen.

Die aktuelle Entwicklungslinie ergänzt hinter dieser Oberfläche jetzt etwas deutlich Tieferes: **begrenztes Tactical Memory und ein erklärbares Intelligence Brain**.

### **Gefahr sehen. Entfernung kennen. Muster verstehen. Früher reagieren.**

---

# 🛰️ WAS SENTINEL WIRD

SENTINEL ist keine weitere statische Map und kein weiteres Killboard.

Es wird als persistenter taktischer Begleiter für Piloten entwickelt, die verstehen wollen:

- was gerade passiert
- wie weit es entfernt ist
- ob es für die eigene Operation relevant ist
- ob aktuelles Verhalten ein nützliches Muster erkennen lässt

Dieselbe Intelligence kann eine Mining-Operation, Hauling-Route, PvE-Pocket oder ein Staging-System schützen — oder Hunters, Scouts und Roamern helfen, aktiven Raum zu finden.

**Gebaut für Miner, Hauler, PvE-Piloten, Explorer, Scouts, Hunter, Roamer, Fleets und Corporations.**

---

# ⚡ AKTUELLE OPERATOR-SYSTEME

### 💀 LIVE KILL MAP
Öffentliche Kill-Aktivität wird gegen den New-Eden-Universe-Graph aufgelöst und in Map-/Distance-Kontext gesetzt.

### 🚨 TACTICAL LIVE MAP WARNING SYSTEM
Relevante Aktivität wird zu einer aktiven Warning-Layer rund um das tatsächlich überwachte System.

### 🛰️ MULTI-CHANNEL INTEL MAP
Vom Benutzer aktivierte Intel-Channels fließen in denselben Tactical-Map- und Monitoring-Kontext ein.

### 🧭 MONITORING ORIGIN
AUTO · MAIN kann dem festgelegten MAIN-Charakter folgen; MANUAL Monitoring kann ein anderes System beobachten, während die Map unabhängig erkundet wird.

### 📍 SYSTEM TOOLTIPS & ROUTE-KONTEXT
Systeme zeigen taktische Historie und gezielte Map-/Route-Aktionen, ohne die Kamera ständig automatisch zu bewegen.

---

# 🧠 0.3.0 ENTWICKLUNGSLINIE

Die größte aktuelle Veränderung passiert hinter der UI.

## Dedizierter Live Relay

SENTINEL betreibt jetzt einen eigenen HTTPS/WSS-Relay unter `relay.sentinel-eve.de` mit sequenzieller öffentlicher R2Z2-Verarbeitung, Reconnect/Resume und begrenzter Live-Auslieferung.

Direct R2Z2 bleibt im Desktop weiterhin die autoritative Live-Quelle, während der Relay als zukünftiger Kandidatenpfad validiert wird.

## Rollierendes 90-Tage Tactical Memory

Aktuelle öffentliche Combat-Beobachtungen können nun in einem begrenzten PostgreSQL-Memory gespeichert werden.

Der Produktionshorizont ist bewusst auf **90 Tage** begrenzt, damit SENTINEL aktuelle taktische Muster erkennen kann, ohne zu einem kostenintensiven dauerhaften Archiv zu werden.

## Tactical Intelligence Brain 1A

Die Pilotanalyse kann beobachtete Muster ableiten zu:

- Ship- und Weapon-Nutzung
- Target Preferences
- wiederkehrenden Co-Attacker-Beziehungen
- historischen Loss-Fit-Familien
- Evidence, Recency und Confidence

## Tactical Intelligence Brain 1B

Das Brain erstellt jetzt außerdem aktuelle Profile für:

- Sonnensysteme
- Corporations
- Alliances
- Attacker-/Victim-Hull-Muster
- UTC-Aktivitätsverteilungen
- wiederkehrende gemeinsam beobachtete Organisationen

SENTINEL hält Inference bewusst ehrlich: historische Fits werden nicht als aktuelle Fits bezeichnet, Co-Attacker nicht automatisch als Fleet Members und Route-/Roam-Rekonstruktion bleibt eine eigene spätere Phase.

---

# 🖥️ WINDOWS-ANWENDUNG

Der aktuelle öffentliche Build enthält bereits:

- MAP INTEL Profile
- Tactical Feed Depth
- Tactical Intelligence Feed
- KILL HEAT
- Tactical Picture
- angepinnte System Tooltips
- SYSTEM VERLAUF
- Local Scan
- MAIN-/Scout-Rollen
- EVE SSO / ESI
- native Windows Alerts
- Dark / Light / OLED Themes
- deutsche und englische UI
- verifizierte One-Click-Updates

SENTINEL unterstützt Gameplay-Entscheidungen und **automatisiert keine Gameplay-Eingaben**.

---

# 🚀 PROJEKTSTATUS

| | |
|---|---|
| **Projekt** | SENTINEL // Tactical Intelligence |
| **Entwickler** | Robocapa |
| **Letzter öffentlicher Windows-Build** | `0.2.30-alpha` |
| **Aktuelle Entwicklungslinie** | `0.3.0-alpha` |
| **Channel** | Alpha / pre-release |
| **Plattform** | Windows x64 |
| **Source Code** | Privat |

### → [SENTINEL Releases](https://github.com/Robocapa-eve/sentinel-releases/releases)
### → [Öffentlicher Development Log](https://github.com/Robocapa-eve/sentinel-releases/blob/main/CHANGELOG.md)
### → [Public Release Repository](https://github.com/Robocapa-eve/sentinel-releases)

Der öffentliche Updater bleibt auf **0.2.30-alpha**, bis ein echter 0.3.0-Windows-Installer existiert und verifiziert wurde.

---

# 🔭 NÄCHSTE RICHTUNG

Die aktuelle Entwicklung bewegt sich in Richtung:

- UI-Integration für das 90-Tage Tactical Memory
- Pilot-/System-/Corporation-/Alliance-Intelligence-Ansichten
- Roam- und Movement-Episode-Inference mit expliziter Confidence
- wahrscheinliche Route-Rekonstruktion
- Content Hotspots / Hostile Pressure / Route Threat
- Watchlist- und Ganker-Group-Intelligence
- breiteres Public-Alpha-Testing

Für die Infrastruktur gilt außerdem eine **GitHub-Zero-Cost-Regel**: Produktionsdatenbank-Speicher wird nicht auf kostenpflichtige GitHub Artifacts, Packages oder Codespaces aufgebaut.

---

<div align="center">

### **KEEP YOUR TOOLS. ADD INTELLIGENCE.**

**Schütze dich. Finde die Action. Verstehe, was jenseits deines Grids passiert.**

<br>

[🇬🇧 English](README.md) · **🇩🇪 Deutsch**

<br><br>

<sub>
SENTINEL ist eine unabhängige Drittanbieter-Anwendung für EVE Online und steht in keiner Verbindung zu CCP Games und wird nicht von CCP Games unterstützt oder empfohlen.<br>
EVE Online und zugehörige Marken sind Eigentum von CCP hf.
</sub>

<br>

**Entwickelt & gepflegt von Robocapa**

</div>
