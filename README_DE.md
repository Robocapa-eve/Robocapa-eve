<div align="center">

<img src="assets/sentinel-logo.png" width="50" alt="SENTINEL Mark">

# SENTINEL // TACTICAL INTELLIGENCE

### Tactical Intelligence für EVE Online

**Private Entwicklung. Evidence first. Gebaut für New Eden.**

`0.4.0-alpha` · `CLOSED DEVELOPMENT` · `WINDOWS x64`

[English](README.md) · **Deutsch**

</div>

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> ROBOCAPA

Ich entwickle **SENTINEL**, eine unabhängige Tactical-Intelligence-Anwendung für **EVE Online**.

Das Projekt folgt einem Grundsatz:

> **Informationen sollen die Reaktionszeit verkürzen — nicht zusätzlichen Lärm erzeugen.**

SENTINEL soll weder eine weitere statische Map noch ein weiteres Killboard sein. Ziel ist eine persistente taktische Command-Oberfläche, die öffentliche Live-Beobachtungen, New-Eden-Kontext, vom Nutzer gelieferte Intelligence und begrenzte historische Evidenz verbindet — ohne alte Daten als vermeintlich sichere Live-Wahrheit darzustellen.

Das Projekt befindet sich aktuell in **geschlossener privater Entwicklung**. Source Code, Release Assets und aktive Entwicklung bleiben privat, bis der Zugang bewusst freigegeben wird.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> CURRENT SIGNAL // 0.4.0-alpha

Die aktive `0.4.0-alpha`-Linie ist der bisher größte SENTINEL-Entwicklungszyklus.

### MAP 2.0

Eine durchgehende New-Eden-Command-Oberfläche mit Semantic LOD, stabiler Universe-Geometrie, echter Stargate-Topologie, Route-/Navigation-Kontext, Territory-/SOV-Layern und tieferen System-/Pilot-/Entity-Intelligence-Flächen.

### OVERWATCH V2

Eine neu aufgebaute Current-Session-Live-Kill-Architektur mit einem akzeptierten Eventstrom für Feed, Map, Heat, Tactical Picture und Kill Bursts. Frischer Prozess bedeutet frische Session; Durable History wird nicht stillschweigend zu Live-Truth.

### Tactical Intelligence

Evidence-backed Analysis umfasst inzwischen Tactical Summary, D-Scan Analyzer, Watchlists 2.0, Combat Hot Zones, Route Risk / Safer Route, Compare Intelligence, Pilot-/System-/Entity-Kontext und begrenzte historische Verhaltensmuster.

### Tactical Memory

Aktuelle öffentliche Combat-Beobachtungen können in einem begrenzten rollierenden 90-Tage-History-Memory gespeichert werden, um recency-aware Analyse, Reconciliation und erklärbare Intelligence zu ermöglichen.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DEVELOPMENT LINE

SENTINEL hat zuletzt drei zentrale Entwicklungsstufen durchlaufen:

| Linie | Bedeutung |
|---|---|
| `0.2.30-alpha` | letzter paketierter Windows-Tactical-Intelligence-Build |
| `0.3.0-alpha` | eingefrorener Live-Relay-/Tactical-Memory-/Intelligence-Brain-Meilenstein |
| `0.4.0-alpha` | aktive MAP-2.0-/OVERWATCH-V2-/Tactical-Intelligence-Entwicklung |

Zur aktuellen Phase gehörte außerdem ein eigener Core Cleanup: obsolete Shadow-/Soak-Pfade wurden entfernt, Live-Authority-Semantik konsolidiert, Simulation von echter Evidenz getrennt, Frontend-Transport/Presentation sauberer getrennt und der Release-Flow auf PR + CI + kontrollierte Promotion gehärtet.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> TRUTH MODEL

SENTINEL folgt:

**OBSERVED → INFERRED → CONFIDENCE**

Diese Trennung ist für EVE-Intelligence entscheidend:

- eine veröffentlichte Killmail belegt das Ereignis, nicht fortbestehende Pilot-Präsenz;
- historische Fits sind keine aktuellen Fits;
- wiederholtes Co-Attacking ist nicht automatisch Fleet Membership;
- Local und D-Scan sind Snapshots und kein permanenter Zustand;
- Route-, Roam- und Behavior-Rekonstruktion muss Evidence und Recency berücksichtigen.

SENTINEL erfindet keine unbelegten Threat- oder Attack-Probabilities.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> OPERATOR FOCUS

Die Anwendung wird für Piloten und Gruppen entwickelt, die besseren Kontext benötigen für:

- Mining- und Industrie-Operationen;
- Hauling und Route Awareness;
- PvE-Pockets und Staging-Systeme;
- Scouting und Roaming;
- Hunting und das Auffinden feindlicher Aktivität;
- Corporation-/Fleet-Situational-Awareness.

Dasselbe Produkt kann helfen, Aktivität zu vermeiden oder sie bewusst zu finden. SENTINEL liefert Kontext; die Entscheidung bleibt beim Spieler.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DATA BOUNDARY

SENTINEL wird entlang legitimer Third-Party-Datenquellen und Nutzerbeobachtungen entwickelt, darunter CCP ESI/SDE, öffentliche Combat-Publikationsdaten, Local-/D-Scan-Clipboard-Snapshots und konfigurierte Intel-Channel-/Log-Evidenz.

Es automatisiert **keine** Gameplay-Eingaben, broadcastet keine Client-Aktionen und manipuliert den EVE-Client nicht.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> RELEASE PHILOSOPHY

Die Entwicklung darf schnell sein; Releases bleiben bewusst kontrolliert.

```text
Feature / Fix / Chore
→ Pull Request
→ vollständige CI
→ stabile Development Foundation
→ Acceptance + Live-QA
→ Release Candidate
→ verifizierter Windows Build
→ Zugangsentscheidung
```

Das Projekt bleibt privat, bis diese letzte Zugangsentscheidung ausdrücklich getroffen wird.

---

<div align="center">

<img src="assets/sentinel-logo.png" width="28" alt="SENTINEL Mark">

### KEEP YOUR TOOLS. ADD INTELLIGENCE.

**Ereignis sehen. Entfernung kennen. Evidenz verstehen. Früher reagieren.**

<sub>SENTINEL ist eine unabhängige Third-Party-Anwendung für EVE Online und steht in keiner Verbindung zu CCP Games und wird nicht von CCP Games unterstützt oder empfohlen. EVE Online und zugehörige Marken sind Eigentum von CCP hf.</sub>

<br><br>

**Entwickelt & gepflegt von Robocapa**

</div>
