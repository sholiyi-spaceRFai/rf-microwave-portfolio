# Ku-Band Low Noise Amplifier (12 GHz)

## 📌 Overview
Design and implementation of a two-stage microstrip low-noise amplifier for satellite receiver front-end applications.

---

## 📊 Performance Summary

| Parameter              | Simulated           | Measured            |
|----------------------|--------------------|--------------------|
| Frequency            | 12 GHz             | ~10.5 GHz          |
| Gain                 | 22 dB              | 15 dB (peak 26 dB) |
| Noise Figure         | ~0.5 dB            | -                  |
| Return Loss          | < -10 dB           | ~ -5 dB            |
| Stability Factor (K) | 1.087              | Stable             |

---

## 🎯 Key Achievements
- Designed **low-noise, high-gain LNA for satellite systems**
- Achieved **K > 1 (unconditionally stable)** :contentReference[oaicite:3]{index=3}
- Optimized **noise vs gain trade-off using Smith chart techniques**

---

## 🧩 Design Highlights
- Technology: Microstrip (RT Duroid 6010)
- Device: NE3210S01 HJFET
- Configuration: 2-stage amplifier
- Tools: ADS simulation

---

## 📈 Engineering Insights
- First stage dominates overall noise performance (Friis equation)
- Matching networks optimized for:
  - Noise figure
  - Gain
  - Stability
- Frequency shift due to fabrication tolerances

---

## 📷 Figures: Links coming soon
- Figure 1 → LNA Block Diagram
- Figure 2 → Stability Circles
- Figure 2-4 → Input Matching Smith Chart
- Figure 3 → Measured Results

---

## 🚀 Applications
Satellite Receivers | RF Front-End | Radar Systems
