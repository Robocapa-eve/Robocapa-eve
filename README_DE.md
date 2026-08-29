<div align="center">

<img src="assets/sentinel-logo.png" alt="SENTINEL Logo">

# S E N T I N E L

### TAKTISCHE INTELLIGENCE FÜR EVE ONLINE

**Taktisches Lagebewusstsein in Echtzeit, hochspezialisierte Live-Intelligence-Überwachung und Map Gefahrenanalyse für New Eden.**

<br>

[🇬🇧 English](README.md) · **🇩🇪 Deutsch**

<br>

![Status](https://img.shields.io/badge/STATUS-AKTIVE%20ENTWICKLUNG-35c98b?style=flat-square)
![Kanal](https://img.shields.io/badge/KANAL-ALPHA-4da3d9?style=flat-square)
![Plattform](https://img.shields.io/badge/PLATTFORM-WINDOWS-737d8c?style=flat-square)
![Version](https://img.shields.io/badge/VERSION-0.2.29--alpha-8b6fd9?style=flat-square)

</div>

---

## SENTINEL

**SENTINEL** ist eine taktische Intelligence- und Lagebewusstseins-Anwendung für **EVE Online**.

Entwickelt für Piloten, die relevante Informationen sofort sehen möchten, ohne während des Spielens mit unnötigem Datenrauschen überladen zu werden, verbindet SENTINEL Live-Intelligence, Kill-Aktivität, Charakterüberwachung, Systeminformationen und taktische Kartendaten in einer fokussierten Windows-Umgebung.

Das Ziel ist einfach:

> **Sieh, was wichtig ist. Verstehe, was passiert. Reagiere, bevor es zum Problem wird.**

### Kernsysteme

- **Live Tactical Map**
- **Vollständige New-Eden-Navigationsdaten**
- **Semantische Deep-Zoom-Karte**
- **EVE Online SSO- & ESI-Integration**
- **Kill-Intelligence in Echtzeit**
- **zKillboard / R2Z2 Live Kill Feed**
- **Intel-Channel-Überwachung**
- **Erkennung mehrteiliger EVE-Charakternamen**
- **System Threat Assessment**
- **Charakter- & Scout-Tracking**
- **Automatische MAIN-Charakterverfolgung**
- **Manuelles taktisches Überwachungszentrum**
- **Konfigurierbare Kill- & Intel-Reichweiten**
- **System Dossiers & taktischer Kontext**
- **Persistenter Tactical Live Feed**
- **Native Windows-Warnsignale**
- **Unabhängige Kill- & Intel-Audioprofile**
- **Windows-System-Tray-Integration**
- **Eigenständiger SENTINEL Windows Client**
- **Sicheres One-Click-Update-System**
- **SHA-256 Release-Verifizierung**
- **Automatischer Neustart nach Updates**

---

## Taktische Überwachung

SENTINEL trennt bewusst den **Kartenfokus** vom tatsächlichen **taktischen Überwachungszentrum**.

Dadurch können Piloten New Eden frei erkunden, ohne versehentlich das System zu verändern, von dem aus taktische Reichweiten berechnet werden.

### AUTO · MAIN

Standardmäßig folgt SENTINEL automatisch dem aktuellen Sonnensystem des als **MAIN** festgelegten Charakters.

Bewegt sich der Pilot durch New Eden, aktualisiert SENTINEL automatisch das Überwachungszentrum und berechnet alle relevanten taktischen Informationen vom neuen Standort aus neu.

Davon betroffen sind unter anderem:

- Kill-Distanzen
- Intel-Distanzen
- Scout-Kontakte
- Watchlist-Informationen
- Gefahrenbewertung
- Native Audio-Warnungen

### MANUELLE Überwachung

Jedes Sonnensystem kann zusätzlich als eigenes taktisches Überwachungszentrum ausgewählt werden.

Dadurch kann ein Pilot beispielsweise ein anderes System, ein Mining-Gebiet, eine Staging-Position, eine Route oder einen strategischen Chokepoint überwachen, während er sich selbst an einem völlig anderen Ort in New Eden befindet.

Mit **MAIN folgen** wird jederzeit sofort wieder die automatische Verfolgung des aktiven MAIN-Charakters aktiviert.

---

## Tactical Map

Die SENTINEL Tactical Map ist als operatives Intelligence-Werkzeug konzipiert und nicht lediglich als statische Universumskarte.

### Kartenfunktionen

- Cursor-zentriertes kontinuierliches Zoomen
- Tiefer taktischer Zoom bis auf Systemebene
- Semantische Detailstufen: Region → Konstellation → System
- Permanente Systemnamen in operativen Zoomstufen
- Interaktive Systemauswahl
- Systemsuche
- System Dossiers
- Darstellung von Sprungdistanzen
- Darstellung des Sicherheitsstatus
- Taktische Ereignismarker
- Threat-Kontext
- Navigations- und Routeninformationen
- Automatische MAIN-Standortverfolgung
- Manuell auswählbares Überwachungszentrum

Das Erkunden oder Fokussieren eines Systems auf der Karte verändert **nicht** automatisch das aktive taktische Überwachungszentrum.

Erst wenn ein Pilot ausdrücklich **Überwachen / Monitor** auswählt, wird dieses System zur neuen taktischen Referenz.

---

## Live Intelligence

SENTINEL führt mehrere Intelligence-Quellen in einer gemeinsamen taktischen Ansicht zusammen.

Angezeigt werden können unter anderem:

- Schiffsverluste
- Mining-Schiffsverluste
- Meldungen aus Intel-Channels
- Scout-Kontakte
- Charakter-Intelligence
- Watchlist-Aktivität
- Charakterbewegungen
- Aktueller MAIN-Standort
- Veränderungen der taktischen Gefahrenlage

Intel-Ereignisse werden normalisiert, aufgelöst und mit den Systemdaten von New Eden abgeglichen, bevor sie dargestellt werden.

Der **Live Intelligence Feed** ist darauf ausgelegt, relevante taktische Ereignisse sichtbar zu machen, ohne interne SENTINEL-Standortinformationen mit echter Intelligence zu vermischen.

---

## Intel-Channel-Überwachung

SENTINEL kann ausgewählte lokale EVE-Online-Chatlogs überwachen und taktische Meldungen in Echtzeit interpretieren.

Der Intelligence-Parser unterstützt:

- Erkennung von Sonnensystemen
- Mehrteilige EVE-Charakternamen
- Numerische Bestandteile in Charakternamen
- Filterung expliziter Intel-Anzahlangaben
- Charakterauflösung
- Taktische Systemzuordnung
- Klassifizierung von Scout- und Hostile-Kontakten

Es werden ausschließlich Channels verarbeitet, die der Nutzer ausdrücklich in SENTINEL aktiviert hat.

---

## Native Windows-Anwendung

SENTINEL läuft als eigenständige Windows-Anwendung und benötigt keinen normalen Browser-Workflow.

### Windows-Integration

- Eigenständiges SENTINEL-Anwendungsfenster
- Native System-Tray-Integration
- Hintergrundbetrieb
- Native Windows-Audio-Warnungen
- Dedizierter lokaler SENTINEL-Dienst
- Automatische Update-Prüfung beim Start
- Saubere Neustartbehandlung
- Eigenständiger Windows-Installer
- Getrennte Anwendungs- und Laufzeitdaten

Lokale Einstellungen und Laufzeitdaten werden getrennt von den installierten Programmdateien gespeichert.

Dadurch kann SENTINEL aktualisiert werden, ohne lokale Konfigurationen oder Benutzereinstellungen zu überschreiben.

---

## Warnsystem

SENTINEL besitzt ein natives Windows-Warnsystem, das dafür ausgelegt ist, auch dann zuverlässig zu funktionieren, wenn EVE Online im Vordergrund läuft.

Für Kill- und Intel-Warnungen können unterschiedliche Audioprofile verwendet werden.

### Verfügbare Warnprofile

- **Sentinel Pulse**
- **Command Alert**
- **Scanner Ping**
- **Deep Warning**

Die Warnreichweiten sind direkt mit den konfigurierten taktischen Sprungreichweiten verbunden.

Das aktuell aktive Überwachungszentrum bestimmt somit, welche Kill-, Intel- und taktischen Ereignisse für SENTINEL relevant sind.

---

## Sichere One-Click-Updates

SENTINEL besitzt eine eigene öffentliche Release- und Update-Infrastruktur.

Beim Start prüft SENTINEL automatisch, ob über den öffentlichen Release-Kanal eine neuere Version verfügbar ist.

Ist die installierte Version aktuell, bestätigt SENTINEL dies direkt auf dem Bildschirm.

Wird eine neuere Version gefunden, kann der Nutzer das Update direkt aus SENTINEL heraus starten.

### Update-Ablauf

`Update erkannt`
→ `Installer wird heruntergeladen`
→ `SHA-256 wird geprüft`
→ `SENTINEL wird sauber beendet`
→ `Installer wird gestartet`
→ `Update wird installiert`
→ `SENTINEL startet automatisch neu`

Ein heruntergeladener Installer wird niemals ausgeführt, bevor seine SHA-256-Prüfsumme exakt mit dem Wert übereinstimmt, der über die SENTINEL Release-Infrastruktur veröffentlicht wurde.

Updates werden außerdem niemals unbeaufsichtigt installiert.

Der Nutzer muss den Update-Vorgang ausdrücklich selbst starten.

### Update-Validierung

Der vollständige reale Update-Pfad wurde erfolgreich getestet:

**SENTINEL 0.2.28-alpha → SENTINEL 0.2.29-alpha**

einschließlich:

- Erkennung des öffentlichen Releases
- Update-Benachrichtigung
- Installer-Download
- SHA-256-Verifizierung
- Installation
- Automatisches Beenden
- Automatischer Neustart
- Verifizierung der neuen Version nach dem Update

---

## Entwicklungsstatus

SENTINEL befindet sich derzeit in **aktiver Alpha-Entwicklung**.

**Aktueller Release-Kanal:** `ALPHA`

**Aktuelle Version:** `0.2.29-alpha`

Der Schwerpunkt der Entwicklung liegt auf:

`Zuverlässigkeit` · `Klarheit` · `Performance` · `Taktischem Lagebewusstsein` · `Sicherheit`

Öffentliche Alpha-Releases und sichere In-App-Updates stehen inzwischen zur Verfügung.

Die Dokumentation wird kontinuierlich erweitert, während SENTINEL auf breitere öffentliche Tests vorbereitet wird.

---

## Projektstruktur

| Ressource | Status |
|---|---|
| SENTINEL Application | 🟢 Aktive Entwicklung |
| Windows Client | 🟢 Aktive Entwicklung |
| Tactical Intelligence | 🟢 Betriebsbereit |
| Tactical Map | 🟢 Betriebsbereit |
| Öffentliche Alpha-Releases | 🟢 Aktiv |
| Automatische Updates | 🟢 Betriebsbereit |
| SHA-256 Release-Verifizierung | 🟢 Betriebsbereit |
| Dokumentation | 🟡 In Vorbereitung |
| EVE Community Listing | ⚪ Zukünftiges Release-Ziel |

---

## Aktueller Meilenstein

### SENTINEL 0.2.29-alpha

Der aktuelle Entwicklungsmeilenstein führt die vollständige SENTINEL Update-Infrastruktur ein und baut gleichzeitig auf den taktischen Monitoring- und Kartensystemen vorheriger Alpha-Versionen auf.

### Highlights

- Sichere öffentliche Release-Erkennung
- Automatische Update-Prüfung beim Start
- Deutsche und englische Update-Benachrichtigungen
- Manuelle Update-Prüfung
- One-Click-Installer-Download
- SHA-256-Verifizierung
- Automatisierte Update-Installation
- Automatischer SENTINEL-Neustart
- Automatische MAIN-Charakterüberwachung
- Manuell auswählbare taktische Überwachungszentren
- Cursor-zentrierter semantischer New-Eden-Zoom
- Tiefer taktischer Kartenzoom
- Permanente Systemnamen in operativen Zoomstufen
- Verbesserte System Dossiers
- Verbesserte Behandlung des Live Intelligence Feeds
- Verbesserte Erkennung von EVE-Charakternamen

---

## Entwicklungsphilosophie

SENTINEL basiert auf einem einfachen Grundsatz:

> **Informationen sollen die Reaktionszeit verkürzen – nicht zusätzlichen Lärm erzeugen.**

Funktionen werden deshalb konsequent für den praktischen Einsatz während des aktiven Spielens von EVE Online entwickelt:

- Wichtige Informationen zuerst
- Möglichst wenig unnötige Interaktion
- Klarer taktischer Kontext
- Gezielte Warnungen statt dauerhaftem Informationsrauschen
- Vorhersehbare Bedienung
- Zuverlässiger Hintergrundbetrieb
- Sichere Update-Verarbeitung

---

<div align="center">

### Entwickelt & gepflegt von Robocapa

**SENTINEL · Tactical Intelligence**

*Sieh, was wichtig ist. Verstehe, was passiert.*

<br>

[🇬🇧 English](README.md) · **🇩🇪 Deutsch**

<br><br>

<sub>
SENTINEL ist eine Drittanbieter-Anwendung für EVE Online und steht in keiner Verbindung zu CCP Games und wird nicht von CCP Games unterstützt oder empfohlen.<br>
EVE Online sowie alle dazugehörigen Marken und Warenzeichen sind Eigentum von CCP hf.
</sub>

</div>
