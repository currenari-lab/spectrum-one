# Spectrum One

![Spectrum One](https://raw.githubusercontent.com/currenari/spectrum-one/main/media/spectrum_one_sm.jpg)

**Spectrum One** is a compact ESP32-based WiFi activity monitor that visualises nearby 2.4 GHz WiFi activity using a 16×2 LCD and a 10-segment LED bar.

It runs repeated WiFi scans and translates wireless packet density and RSSI signal levels into live, visible data: real-time signal bars, numerical metrics, and responsive LED bargraph indicators.

---

## Complete Documentation & Build Book (PDF)

A complete, illustrated engineering and assembly book is included with the project:

**[ESP32 WiFi Activity Monitor — Complete Build Guide (PDF)](docs/ESP32%20WiFi%20Activity%20Monitor.pdf)**  
*(Direct Download: [ESP32 WiFi Activity Monitor.pdf](https://raw.githubusercontent.com/currenari/spectrum-one/main/docs/ESP32%20WiFi%20Activity%20Monitor.pdf))*

**Book Contents:**
* Full circuit theory and hardware schematics
* Component selection & BOM (Bill of Materials)
* PCB assembly, soldering, and casing fabrication
* ESP-IDF firmware flashing and calibration walkthrough

---

## Open Hardware Certification

<a href="https://certification.oshwa.org/uk000086.html">
  <img src="media/certification/oshwa/certification-mark-UK000086-wide.png" width="220" alt="OSHWA certification UK000086">
</a>

* **OSHWA UID:** [UK000086](https://certification.oshwa.org/uk000086.html)
* **Certified Hardware Version:** 0.1.0
* **Full Record:** [`CERTIFICATION.md`](CERTIFICATION.md)

---

## Repository Contents

* **`docs/`**: Technical documentation and the complete [**ESP32 WiFi Activity Monitor Book (PDF)**](docs/ESP32%20WiFi%20Activity%20Monitor.pdf).
* **`hardware/`**: KiCad schematics, PCB layouts, Gerber files, BOM, and assembly outputs.
* **`firmware/`**: ESP-IDF C/C++ firmware source code.
* **`binaries/`**: Pre-compiled reference binaries for 1-click flashing.
* **`media/`**: High-resolution diagrams, schematics, and device photographs.

---

## Hardware Assembly

Detailed assembly guides and mechanical documentation:
* General Assembly: [`ASSEMBLY.md`](ASSEMBLY.md)
* Version 0.1.0 Guide: [`hardware/v0.1.0/ASSEMBLY.md`](hardware/v0.1.0/ASSEMBLY.md)

---

## Licensing

* **Firmware Source Code & Binaries:** [MIT License](LICENSE.md)
* **Hardware Design Files & PCB Layouts:** [CERN Open Hardware Licence v2.0 Strongly Reciprocal (CERN-OHL-S-2.0)](LICENSE.md)
* **Documentation & Media:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE.md)

*(C) 2026 Currenari. All rights reserved.*