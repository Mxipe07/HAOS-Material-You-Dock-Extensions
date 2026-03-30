<div align="center">
  <img src="./images/00-haos-view-dark.png" alt="HAOS Material You Dock Preview" width="100%">
  <h1 align="center">HAOS Material You Dock</h1>
  <p align="center">
    Modernes Home Assistant UI im Material You Stil mit Bottom Dock, Swipe Tabs und Feature Cards.
  </p>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Home_Assistant-Dashboard-41BDF5?style=for-the-badge">
  <img src="https://img.shields.io/badge/style-Material_You-8b9cf6?style=for-the-badge">
  <img src="https://img.shields.io/badge/license-MIT-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/platform-Android_%26_iOS-4caf50?style=for-the-badge">
</p>

---

## Überblick

**HAOS Material You Dock** ist ein modernes, mobiles Dashboard-UI für Home Assistant.  
Das Projekt enthält wiederverwendbare YAML-Komponenten für:

- Bottom Dock Navigation
- Swipe Tabs / Filterleisten
- Feature Cards

Optimiert für **Dark Mode** und **Light Mode**.

---

## Vorschau

### Dashboard

| Dark Mode | Light Mode |
|---|---|
| ![](./images/00-haos-view-dark.png) | ![](./images/00-haos-view-light.png) |

---

## Komponenten

## Bottom Dock Navigation

| Dark | Light |
|---|---|
| ![](./images/01-bottom-dock-dark.png) | ![](./images/01-bottom-dock-light.png) |

Fixierte Navigation am unteren Bildschirmrand mit aktiven Zuständen, Animationen und Theme-Anpassung.

### Datei
`01-bottom-dock.yaml`

### Anpassbar
- `navigation_path`
- Icons
- Labels
- optionale Profil-/Avatar-Quelle

---

## Swipe Tabs

| Dark | Light |
|---|---|
| ![](./images/02-swipe-tabs-dark.png) | ![](./images/02-swipe-tabs-light.png) |

Horizontale Tab-Leiste mit dynamischen Pills und Swipe-Verhalten.

### Datei
`02-swipe-tabs.yaml`

### Anpassbar
- aktive Helper-Entity
- Tab-Namen
- Icons
- Optionen / Zustände

---

## Feature Cards

| Dark | Light |
|---|---|
| ![](./images/03-feature-cards-dark.png) | ![](./images/03-feature-cards-light.png) |

Material-inspirierte Schnellzugriffskarten für wichtige Dashboard-Bereiche.

### Datei
`03-feature-cards.yaml`

### Anpassbar
- `navigation_path`
- Icons
- Farben
- Beschriftungen

---

## Features

- Material You inspirierter Look
- Dark / Light Mode Support
- Flüssige Animationen
- Mobile optimiert
- Wiederverwendbare YAML-Komponenten
- Einfache Anpassung an eigene Dashboards

---

## Voraussetzungen

- Home Assistant
- `button-card`
- `card-mod`
- `swipe-card`

**Empfohlen:**
- Material You Theme oder eigenes angepasstes Theme

---

## Installation

1. YAML-Dateien in dein Dashboard übernehmen
2. Eigene Entitäten und `navigation_path` anpassen
3. Optional Theme aktivieren
4. Fertig

---

## Dateien

- `01-bottom-dock.yaml` → Bottom Navigation
- `02-swipe-tabs.yaml` → Tabs / Filterleiste
- `03-feature-cards.yaml` → UI Karten

---

## Hinweise

Die verwendeten Navigationen wie z. B. `#cameras`, `#lighting` oder `#climate` sind Platzhalter und müssen an dein eigenes Dashboard angepasst werden.

---

## Lizenz

MIT License
