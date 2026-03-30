<div align="center">

  <h1>Material You Dock Extensions</h1>

  <p><b>Modernes Home Assistant UI im Material You Stil</b><br>
  Bottom Dock • Swipe Tabs • Feature Cards</p>

  <p>
    <img src="https://img.shields.io/badge/Home_Assistant-Dashboard-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white">
    <img src="https://img.shields.io/badge/style-Material_You-8b9cf6?style=for-the-badge">
    <img src="https://img.shields.io/badge/license-MIT-black?style=for-the-badge">
    <img src="https://img.shields.io/badge/platform-Android_%26_iOS-4caf50?style=for-the-badge&logo=android&logoColor=white">
  </p>

  <p>
    <a href="https://github.com/smarthomebutbetter/HAOS-Material-You-Dock-Extensions/stargazers">
      <img src="https://img.shields.io/github/stars/smarthomebutbetter/HAOS-Material-You-Dock-Extensions?style=social">
    </a>
    <a href="https://github.com/smarthomebutbetter/HAOS-Material-You-Dock-Extensions/issues">
      <img src="https://img.shields.io/github/issues/smarthomebutbetter/HAOS-Material-You-Dock-Extensions">
    </a>
    <a href="https://github.com/smarthomebutbetter/HAOS-Material-You-Dock-Extensions/commits">
      <img src="https://img.shields.io/github/last-commit/smarthomebutbetter/HAOS-Material-You-Dock-Extensions">
    </a>
  </p>

  <p><b>⚡ Schnell starten:</b> YAML kopieren → anpassen → fertig</p>

</div>

---

## ✨ Überblick

**HAOS Material You Dock** ist ein modernes, mobiles Dashboard-UI für Home Assistant.

Das Projekt bietet wiederverwendbare Komponenten für ein sauberes, performantes und modernes UI:

- Bottom Dock Navigation  
- Swipe Tabs / Filterleisten  
- Feature Cards  

Optimiert für **Dark Mode / Light Mode** und mobile Nutzung.

---

## 📸 Vorschau

### Dashboard

| Dark Mode | Light Mode |
|---|---|
| ![Dark](./images/00-haos-view-dark.png) | ![Light](./images/00-haos-view-light.png) |

---

## 🧩 Komponenten

### Bottom Dock Navigation

| Dark | Light |
|---|---|
| ![Dark](./images/01-bottom-dock-dark.png) | ![Light](./images/01-bottom-dock-light.png) |

Fixierte Navigation am unteren Bildschirmrand mit Animationen und Theme-Anpassung.

**Datei:** `01-bottom-dock.yaml`

**Anpassbar:**
- Navigation (`navigation_path`)
- Icons & Labels
- Avatar / Profilbild

---

### Swipe Tabs

| Dark | Light |
|---|---|
| ![Dark](./images/02-swipe-tabs-dark.png) | ![Light](./images/02-swipe-tabs-light.png) |

Horizontale Tab-Leiste mit dynamischen Pills und Swipe-Verhalten.

**Datei:** `02-swipe-tabs.yaml`

**Anpassbar:**
- Helper-Entity
- Tabs & Icons
- Zustände / Filter

---

### Feature Cards

| Dark | Light |
|---|---|
| ![Dark](./images/03-feature-cards-dark.png) | ![Light](./images/03-feature-cards-light.png) |

Material-inspirierte Schnellzugriffskarten für wichtige Bereiche.

**Datei:** `03-feature-cards.yaml`

**Anpassbar:**
- Navigation (`navigation_path`)
- Icons
- Farben
- Texte

---

## 🚀 Features

- Material You Design  
- Dark / Light Mode Support  
- Flüssige Animationen  
- Mobile optimiert  
- Modular & wiederverwendbar  
- Einfach anpassbar  

---

## ⚙️ Voraussetzungen

- Home Assistant  

### 🔌 Benötigte Karten / Add-ons

- 🔘 [button-card](https://github.com/custom-cards/button-card) von [RomRider](https://github.com/romrider)  
  → flexible UI Karten (Basis für Dock & Feature Cards)

- 🎨 [card-mod](https://github.com/thomasloven/lovelace-card-mod) von [thomasloven](https://github.com/thomasloven)  
  → Styling, CSS, Material Look

- 👉 [swipe-card](https://github.com/bramkragten/swipe-card) von [bramkragten](https://github.com/bramkragten)  
  → Swipe Navigation für Tabs

---

### 🎨 Theme (empfohlen)

👉 Für den besten Look:

- 🌈 [Material You Theme (Beispiel)](https://github.com/Nerwyn/material-rounded-theme)  
  → gute Basis für Material Design

ODER

- ✨ eigenes angepasstes Theme  
  → empfohlen für maximale Kontrolle (dein Stil)

---

💡 Tipp:  
Alle Karten lassen sich einfach über **HACS installieren**.
---

## 📦 Installation

```bash
git clone https://github.com/smarthomebutbetter/HAOS-Material-You-Dock-Extensions.git
