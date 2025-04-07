# Layout

This folder contains the physical layout of the two-stage Operational Amplifier designed using Cadence Virtuoso 90nm technology.

## 🧱 Overview
The layout was created after schematic-level verification and includes:
- Proper device sizing
- Matching techniques
- Symmetric layout for differential stages
- Guard rings and shielding (if used)

## 📁 Contents
- `opamp_layout.png` – Screenshot of the final layout
- `drc_result.png` – DRC check result image (optional)
- `lvs_result.png` – LVS result image (optional)
- `layout_notes.pdf` – Notes or report on layout constraints and challenges (optional)

## 🛠️ Tool Used
- Cadence Virtuoso Layout Editor
- PDK: 90nm CMOS

## 📌 Highlights
- DRC Clean ✅
- LVS Matched ✅
- Area Efficient 🌟

## 📝 Tip
Ensure that parasitic capacitances are minimized, especially at the output node.
