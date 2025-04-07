# Transient Simulation

This folder contains the transient simulation results of the two-stage Operational Amplifier designed using Cadence Virtuoso 90nm.

## 📈 Purpose
The transient analysis helps verify:
- Time-domain response of the amplifier
- Slew rate performance
- Settling behavior
- Output waveform under dynamic input conditions

## 📁 Contents
- `transient_output.png` – Simulated output waveform of the Op-Amp
- `input_vs_output.png` – Comparison of input stimulus and output response (optional)

## ⚙️ Setup Info
- Testbench: Pulse or step input
- Load Capacitance: XX fF (fill this when you know it)
- Supply Voltage: XX V

## 🛠️ Tool Used
- Cadence Virtuoso ADE (90nm)

## 💡 Tip
You can measure slew rate from the steepest slope of the output curve during transition.


