# AC Simulation

This folder contains the AC simulation results of the two-stage Operational Amplifier implemented in Cadence Virtuoso 90nm.

## 🎯 Purpose
The AC analysis is performed to evaluate the frequency-domain performance of the Op-Amp. It helps determine:
- Gain
- Bandwidth (BW)
- Phase Margin (PM)
- Unity Gain Bandwidth (UGBW)

## 📁 Contents
- `ac_gain_plot.png` – Gain vs. frequency plot (dB scale)
- `phase_plot.png` – Phase vs. frequency plot (optional)
- `bode_plot.png` – Combined Bode plot (gain and phase)

## ⚙️ Setup Info
- Input: AC signal with small amplitude
- Sweep Type: Logarithmic frequency sweep
- Frequency Range: 1Hz to 100MHz (or as required)

## 🛠️ Tool Used
- Cadence Virtuoso ADE
- PDK: 90nm CMOS

## 📝 Notes
- Ensure proper biasing before running AC simulations.
- Stability can be inferred from phase margin and gain margin.
