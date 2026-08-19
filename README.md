<div align="center">

<!-- Animated Progress Race Line -->
<img src="Progress/progress.svg" alt="Mission Progress" width="100%"/>

<br/><br/>

# 🛰️ 1U-CubeSat — SYSTEM-3

**Stony Brook University Nanosatellite Division**

*Open-Source Gamma-Ray Spectrometer CubeSat Mission*

[![Mission Status](https://img.shields.io/badge/STATUS-IN_DEVELOPMENT-orange?style=for-the-badge&labelColor=0f0f1a)](https://github.com)
[![License](https://img.shields.io/badge/LICENSE-MIT-green?style=for-the-badge&labelColor=0f0f1a)](LICENSE)
[![Open Source](https://img.shields.io/badge/OPEN_SOURCE-100%25-brightgreen?style=for-the-badge&labelColor=0f0f1a)](https://github.com)

</div>

---

## 📡 Mission Overview

<!-- TODO: Edit this section with your mission description -->

> *A 1U CubeSat designed and built by students at Stony Brook University for low-Earth orbit gamma-ray background radiation measurements. All data, designs, and code are fully open-source.*

---

## 📂 Repository Structure

```
├── CAD/                  → 3D CAD files (Fusion 360, STEP, STL)
├── EasyEDA_Gerbers/      → EasyEDA Pro schematics & Gerber fabrication files
├── Code/                 → Flight firmware & ground station software
├── Physics/              → Radiation physics simulations & analysis
├── Materials/            → Component datasheets, BOMs, vendor specs
├── Proposals/            → Mission proposals & documentation
├── Progress/             → Milestone tracking & progress animations
├── docs/                 → GitHub Pages website source
└── index.html            → Project landing page
```

---

## 🏗️ Hardware Architecture

| Stage | Dimensions | Subsystem |
|-------|-----------|-----------|
| 1 | 95.0 × 95.0 mm | CsI(Tl) Scintillator + SiPM Array |
| 2 | 95.0 × 95.0 mm | Analog Front-End Pico Spectrometer |
| 3 | 95.0 × 95.0 mm | C&DH Flight Core (STM32F411) |
| 4 | 95.0 × 95.0 mm | EPS Solar Power Manager |
| 5 | 95.0 × 95.0 mm | Battery + UHF Transceiver |
| 6 | 95.0 × 95.0 mm | Antenna Deployment Deck |

---

## 📻 RF Downlink

- **Frequency:** 437.025 MHz UHF
- **Protocol:** AX.25 / 9600 Baud GFSK
- **Tracking:** SatNOGS Global Network
- **Encryption:** None — 100% public science telemetry

---

## 🚀 Getting Started

<!-- TODO: Add setup instructions -->

```bash
# Clone the repository
git clone https://github.com/<your-org>/1U-CubeSat.git
cd 1U-CubeSat
```

---

## 🤝 Contributing

<!-- TODO: Add contribution guidelines -->

This is an open-source project. Contributions welcome!

---

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">
<sub>Built with 🔥 by the Stony Brook University Nanosatellite Division</sub>
</div>
