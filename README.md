<div align="center">

  <h1>HAOS 
Material You Dock Extensions</h1>

  <p><b>Modernes Home Assistant UI im Material You Stil</b><br>
  Bottom Dock • Swipe Tabs • Feature Cards</p>

  <p>
    <img src="https://img.shields.io/badge/Home_Assistant-Dashboard-41BDF5?style=for-the-badge&logo=homeassistant&logoColor=white">
    <img src="https://img.shields.io/badge/style-Material_You-8b9cf6?style=for-the-badge">
    <img src="https://img.shields.io/badge/license-MIT-black?style=for-the-badge">
    <img src="https://img.shields.io/badge/platform-Android_%26_iOS-4caf50?style=for-the-badge&logo=android&logoColor=white">
  </p>

  <p>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Extensions/stargazers">
      <img src="https://img.shields.io/github/stars/Mxipe07/HAOS-Material-You-Dock-Extensions?style=social">
    </a>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Extensions/issues">
      <img src="https://img.shields.io/github/issues/Mxipe07/HAOS-Material-You-Dock-Extensions">
    </a>
    <a href="https://github.com/Mxipe07/HAOS-Material-You-Dock-Extensions/commits">
      <img src="https://img.shields.io/github/last-commit/Mxipe07/HAOS-Material-You-Dock-Extensions">
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
- `button-card`  
- `card-mod`  
- `swipe-card`  

👉 Empfohlen: Material You Theme oder eigenes Theme

---

## 📦 Installation

```bash
git clone https://github.com/Mxipe07/HAOS-Material-You-Dock-Extensions.git