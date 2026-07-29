# DIY FIN Condenser Microphone Project 🎙️

An open-source repository for building a compact studio condenser microphone based on the **FIN circuit** (an ultra-low-noise, transformerless microphone topology).

This repository contains the Bill of Materials (BOM), component sourcing guides (with local Prague options), and build progress notes.

---

## 🚀 Project Status & Roadmap

> **Current Status:** In Progress 🛠️

This project is currently in its early stages and will be updated step-by-step as I progress. 

Since not all components are readily available off-the-shelf in local electronic stores (e.g., 3GΩ resistors, specific JFETs, and inductors), I will be finding workarounds, testing component substitutes, and documenting all sourcing solutions along the way.

---

## 📖 Project Background & Story

I stumbled upon a YouTube Short by **[Alexey Kostrykin](https://www.youtube.com/@AlexeyKostrykin/shorts)** titled *["Микрофон по схеме FIN"](https://www.youtube.com/shorts/0v5QWER9Aq8)*. I was really impressed by the audio quality demonstrated in the video (which was voiced using the microphone itself!) and decided to build one for myself.

The author kindly provided a public **[Google Drive Folder](https://drive.google.com/drive/folders/1b-6JGVSPCHNgb5s343AQEgBrW2yjJV4H?usp=drive_link)** containing schematic diagrams, PCB layouts, test audio files, and assembly guides. This repository tracks my journey of sourcing parts, substituting legacy components, and assembling the microphone.

---

## 🛠️ Bill of Materials (BOM)

### 1. Capsule
* **Capsule:** 26mm Condenser Capsule *(Purchased via eBay)*

### 2. Standard Components (Sourced via GM Electronic, Prague)
| # | Component | Value / Part | Qty | Notes |
|---|---|---|---|---|
| 1 | Resistor | 47Ω | 2x | Metal Film 0.6W 1% |
| 2 | Resistor | 47kΩ | 2x | Metal Film 0.6W 1% |
| 3 | Resistor | 2MΩ | 1x | Metal Film 0.6W 1% |
| 4 | Resistor | 1MΩ | 1x | Metal Film 0.6W 1% |
| 5 | Resistor | 6.8Ω (6R) | 1x | Metal Film 0.6W 1% |
| 6 | Resistor | 12kΩ | 1x | Metal Film 0.6W 1% |
| 7 | Resistor | 5.6kΩ | 1x | Metal Film 0.6W 1% |
| 8 | Capacitor | 47µF | 2x | Electrolytic (25V–50V) |
| 9 | Capacitor | 470µF | 1x | Electrolytic (25V–50V) |
| 10 | Capacitor | 680pF | 2x | Film / High-quality Ceramic |
| 11 | Capacitor | 1000pF (1nF) | 1x | Film / High-quality Ceramic |
| 12 | Transistor | BC857B | 1x | PNP Transistor |
| 13 | Transistor | BC847C | 1x | NPN Transistor |
| 14 | Diode | LL4148 / 1N4148 | 1x | Signal Diode |
| 15 | Connector | XLR Male 3-Pin | 1x | Panel Mount Connector |

### 3. Special & High-Gigohm Components (Sourced via Mouser / TME)
* **High-Gigohm Resistors:** 3GΩ (3 Gigaohm) — 2x *(Capsule polarization circuit)*
* **Inductor:** 0.7µH — 2x
* **JFET Transistor:** MMBF5457 (SOT-23) + SOT-23 to DIP adapter board *(Direct replacement for the obsolete 2N5457 TO-92)*

---

## 🛒 Local Sourcing Notes (Prague, Czech Republic)
* **GM Electronic (Křižíkova 147/77, Prague 8):** Local pick-up for standard passive components, XLR connector, and BC/LL transistors (~120–150 CZK total).
* **Mouser / TME:** Online order for 3GΩ resistors, MMBF5457 JFET, and 0.7µH inductors.

---

## 📂 Repository Structure
* `/schematics` — Original FIN schematics and PCB designs.
* `/photos` — Build progress and final microphone photos.
* `/docs` — Component datasheets and workaround guides.
