# Artemis — Astronomy, Stargazing & Telescope Controller

Artemis is an offline-first astronomy application, sky map visualizer, and astrophotography telescope controller for Android and Desktop (Qt 6 with a **Vulkan 1.3 and DirectX 12 (Feature Level 12_1) First/Only** graphics rendering architecture). Designed for stargazers and amateur astronomers, Artemis features real-time celestial sphere calculations, deep-sky object catalogs, satellite tracking, and INDI/ASCOM telescope mount control.

---

## ⚡ Core Subsystems & Status Matrix

| Subsystem | Features & Capabilities | Status / Roadmap |
|---|---|---|
| **Graphics Engine** | **Vulkan 1.3 & DirectX 12 (Feature Level 12_1) First/Only** desktop viewport | Active |
| **Sky Map Renderer** | Real-time celestial sphere rendering, star/constellation map, night vision red-mode | Active |
| **Deep-Sky Catalogs** | High-res Messier, NGC, and IC deep-sky object overlays, 3D solar system orbits | Roadmap |
| **Satellite Tracker** | TLE orbital calculator, ISS pass predictor, sky transit alerts | Active |
| **AR & TLE Importer** | Custom TLE list importer, satellite flare predictor, AR sky overlay | Roadmap |
| **Equipment Control** | INDI & ASCOM telescope mount connection driver, GoTo alignment, camera control | Active / Expanding |
| **Astrophotography** | Automated polar alignment wizard, auto-guiding integration, plate solving engine | Roadmap |

---

## 🌌 Key Features & Module Breakdown

### 🔭 Interactive Sky Map & Planetarium (`sky-map`)
- **Current**: Real-time celestial sphere rendering, star/constellation map, solar system planet position calculator, and night vision red-mode view.
- **Planned / Roadmap**: Deep-sky object (Messier, NGC, IC catalogs) high-res overlay, 3D solar system orbits, and meteor shower tracker.

### 🛰️ Satellite & ISS Tracking (`satellites`)
- **Current**: TLE orbital calculation engine, International Space Station (ISS) pass predictor, and sky transit alerts.
- **Planned / Roadmap**: Custom TLE list importer, satellite flare predictor, and AR (Augmented Reality) sky overlay.

### 📡 Telescope & Equipment Control (`hardware`)
- **Current**: INDI / ASCOM telescope mount connection driver, GoTo target alignment, and camera exposure controller.
- **Planned / Roadmap**: Automated polar alignment wizard, auto-guiding integration, and plate solving alignment engine.

---

## 🏗️ Architecture & Technology Stack

- **Graphics APIs**: Vulkan 1.3 & DirectX 12 (Feature Level 12_1) First/Only.
- **UI Shell**: Qt 6.12 / QML for Desktop, Jetpack Compose for Android.
- **Core Engine**: C++20 astronomical calculation kernel (`SOFA` / `SPICE` math libraries).
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

### Desktop
```bat
build.bat Release
run.bat
```

---

## 📜 License

Artemis is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
