<div align="center">

<img src="assets/sentinel-logo.png" width="54" alt="SENTINEL Mark">

# SENTINEL // TACTICAL INTELLIGENCE

### Ein Live-Intelligence-System für EVE Online

**Live Kills in Range. Intel-Channel-Aktivität auf der Map. Pilot Intelligence darunter.**

`0.4.0-alpha` · `CLOSED DEVELOPMENT` · `WINDOWS x64`

[English](README.md) · **Deutsch**

</div>

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> ROBOCAPA // ENGINEERING NEW EDEN INTELLIGENCE

Ich entwickle **SENTINEL**, eine unabhängige Tactical-Intelligence-Plattform für **EVE Online**.

Was mit einer praktischen Frage begann — *kann ich relevante Kills und Intel-Meldungen in meiner Umgebung direkt auf einer Live Map sehen?* — ist inzwischen zu einem deutlich größeren System gewachsen.

Heute ist die Map nur noch die sichtbare Oberfläche.

SENTINEL empfängt öffentliche Live-Combat-Beobachtungen und ausdrücklich konfigurierte Intel-Channel-Evidenz, setzt diese in die reale New-Eden-Topologie und korreliert die neuen Signale anschließend mit der taktischen Evidenz, die dem System bereits zur Verfügung steht.

Für jeden beobachteten Piloten, jede Corporation, Alliance und jedes System mit ausreichender Evidenz kann SENTINEL Kontext bereitstellen wie:

- Aktivitätsfenster und wiederkehrende Systeme;
- beobachtete Hull- und Waffennutzung;
- historische Fitting-Familien;
- wiederkehrende Co-Attacker und Gang-Tendenzen;
- Roaming-/Corridor-Evidenz und Movement Episodes;
- Target Preferences und Verhaltensmuster;
- aktuelle Route Exposure und Safer-Route-Kontext;
- Aktivitäts-Baselines für Systeme, Corporations und Alliances;
- Live-Ereignisse im direkten Vergleich mit begrenztem Tactical Memory.

> **Das Live-Ereignis ist nur der Anfang. SENTINEL versucht, das taktische Lagebild dahinter zu erklären.**

Historische Evidenz wird niemals stillschweigend als aktuelle Wahrheit dargestellt. Ein historischer Fit ist kein aktueller Fit. Ein rekonstruierter Korridor ist kein bewiesener Reiseweg. Wiederkehrende Co-Attacker sind nicht automatisch Fleet Members.

Diese Trennung ist Bestandteil des Produkts und kein Disclaimer, den wir nachträglich ankleben.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> LIVE MAP // THE FRONT LINE

### LIVE KILLS IN RANGE

Akzeptierte Current-Session-Combat-Ereignisse erscheinen im taktischen Kartenkontext rund um den Operator. Dieselben akzeptierten Event-IDs versorgen Map, Live Feed, Heat, Tactical Picture und Kill Bursts.

### INTEL CHANNEL LIVE MAP

Ausdrücklich konfigurierte EVE-Intel-Channels werden lokal verarbeitet, über Multibox-Logs hinweg dedupliziert und mit einer eigenen vom Operator kontrollierten Intel Range auf dieselbe taktische Karte und in denselben Live Intelligence Feed projiziert.

### ONE OPERATING PICTURE

Local Snapshots, D-Scan, Scouts, Watchlists, öffentliche Kills und Intel-Meldungen werden nicht als voneinander getrennte Widgets behandelt. Sie laufen in einer gemeinsamen Live-Command-Oberfläche zusammen.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> INTELLIGENCE ENGINE // WHAT RUNS UNDERNEATH

Die `0.4.0-alpha`-Linie entwickelt SENTINEL deutlich über ein Live-Map-Tool hinaus zu einer persistenten Intelligence-Schicht.

Neue Beobachtungen können mit begrenzter aktueller Evidenz korreliert werden und Pilot-, System-, Corporation- und Alliance-Intelligence aufbauen. Dazu gehören Tactical Summary, D-Scan Analyzer, Watchlists 2.0, Combat Hot Zones, Route Risk / Safer Route, Compare Intelligence, Hunter Trails, wiederkehrende Aggressor Networks und evidence-backed Behavior Context.

Das Arbeitsprinzip bleibt klar:

**OBSERVED → INFERRED → CONFIDENCE**

SENTINEL erfindet keine unbelegten Threat- oder Attack-Probabilities und behauptet keine Informationen, die seine Datenquellen nicht liefern können.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> CURRENT DEVELOPMENT // 0.4.0-alpha

**MAP 2.0** — eine durchgehende New-Eden-Command-Oberfläche mit Semantic LOD, echter Stargate-Topologie, Navigation-/Route-Kontext, SOV-/Territory-Layern und tiefen Pilot-/System-/Entity-Flächen.

**OVERWATCH V2** — dedizierte Current-Session-Live-Kill-Architektur für Feed, Map, Heat, Tactical Picture und Kill Bursts mit sauberer Fresh-Process-Session-Truth und begrenztem Fallback-Verhalten.

**Tactical Memory** — rollierendes 90-Tage-PostgreSQL-Memory für aktuelle öffentliche Combat-Beobachtungen mit Provenance, Reconciliation und read-only Intelligence-Konsumenten.

**Tactical Intelligence** — evidence-backed Analyse von Piloten, Systemen, Corporations, Alliances, Route Pressure, Roaming-Mustern, Gang-Tendenzen und historischer Fit-Evidenz.

Das Projekt bleibt in **geschlossener privater Entwicklung**, bis Zugang bewusst freigegeben wird.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DEVELOPMENT LINE

| Linie | Bedeutung |
|---|---|
| `0.2.30-alpha` | letzter paketierter Windows-Tactical-Intelligence-Build |
| `0.3.0-alpha` | eingefrorener Live-Relay-/Tactical-Memory-/Intelligence-Brain-Meilenstein |
| `0.4.0-alpha` | aktive MAP-2.0-/OVERWATCH-V2-/Tactical-Intelligence-Entwicklung |

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

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> DATA BOUNDARY

SENTINEL wird entlang legitimer EVE-Third-Party-Datenpfade entwickelt: CCP ESI/SDE, öffentliche Combat-Publikationsevidenz, explizite Local-/D-Scan-Clipboard-Snapshots und ausdrücklich konfigurierte Intel-Channel-/Log-Beobachtungen.

Es automatisiert **keine** Gameplay-Eingaben, broadcastet keine Client-Aktionen und manipuliert den EVE-Client nicht.

---

## <img src="assets/sentinel-logo.png" width="18" alt=""> PROJECT HOME

**Robocapa-eve auf GitHub:** https://github.com/Robocapa-eve

SENTINEL Source Development und der private Release Vault werden unter diesem Account gepflegt, solange sich das Projekt in geschlossener Entwicklung befindet.

---

<div align="center">

<img src="assets/sentinel-logo.png" width="30" alt="SENTINEL Mark">

### KEEP YOUR TOOLS. ADD INTELLIGENCE.

**Live Signal rein. Taktischer Kontext raus.**

**Ereignis sehen. Entfernung kennen. Die Piloten dahinter verstehen. Früher reagieren.**

<sub>SENTINEL ist eine unabhängige Third-Party-Anwendung für EVE Online und steht in keiner Verbindung zu CCP Games und wird nicht von CCP Games unterstützt oder empfohlen. EVE Online und zugehörige Marken sind Eigentum von CCP hf.</sub>

<br><br>

**Entwickelt & gepflegt von Robocapa**

</div>
