# Two-Stage Operational Amplifier – Cadence Virtuoso 90nm

This project involves the complete design, simulation, and layout of a **Two-Stage CMOS Operational Amplifier** using **Cadence Virtuoso** with a **90nm CMOS process**.

---

## 🎯 Objective
To design a high-gain, stable two-stage Op-Amp that meets the essential analog performance metrics such as gain, phase margin, and bandwidth, suitable for analog signal processing applications.

---

## 🧪 Technology Node
- **90nm CMOS** (Generic PDK)

---

## 📊 Key Specifications (Target)
| Parameter        | Target Value    |
|------------------|-----------------|
| Open-loop Gain   | ≥ 60 dB         |
| Phase Margin     | ≥ 60°           |
| Unity Gain BW    | ≥ 10 MHz        |
| Slew Rate        | > 20 V/µs        |
| Output Swing     | Rail-to-Rail    |
| Power Supply     | 1.5V            |

---

## 🛠️ Tools Used
- Cadence Virtuoso (Schematic/Layout)
- ADE (DC, AC, Transient simulations)
- DRC & LVS (Physical verification)

---

## 📁 Folder Structure

| Folder        | Description                                      |
|---------------|--------------------------------------------------|
| `schematic/`  | Schematic design files and screenshots           |
| `transient/`  | Transient simulation and slew rate measurement   |
| `dc/`         | DC simulation setup and plots                    |
| `ac/`         | Frequency-domain (Bode) analysis results         |
| `layout/`     | Physical layout images and verification results  |
| `reports/`    | Optional: Hand calculations, design notes, etc.  |

---

## ✅ Current Status

- [x] Schematic completed
- [x] Transient simulation completed
- [ ] DC analysis
- [ ] AC analysis
- [ ] Layout
- [ ] DRC / LVS verification
- [ ] Final performance summary

---

## 📌 Notes
- Matching techniques and layout best practices are followed to ensure optimal performance.
- All simulations are validated in Virtuoso ADE.

---
