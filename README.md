<div align="center">

# Hari S
### Embedded Systems Engineer — Firmware · Sensing · Communication Hardware

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hari-sakthivel-2532a1384)
[![Email](https://img.shields.io/badge/Email-333?style=flat-square&logo=gmail&logoColor=white)](mailto:harisakthivel2128@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hari2128-cell)

</div>

---

## Engineering Philosophy

I build systems that work in the field, not just on a breadboard in ideal conditions. My focus is on hardware-software co-design: circuits that condition and protect signals correctly, and firmware that reads them reliably under real-world noise and power constraints. I care more about a system surviving a power brownout or a bad connector than about adding one more feature. Most of my projects grew out of a constraint — no cellular network, no microcontroller budget, no line of sight — and the engineering decisions in each one reflect that constraint.

---

## Engineering Focus

- Embedded C / Arduino-based firmware
- Analog signal conditioning and sensor interfacing
- Long-range wireless communication (LoRa)
- GPS-based positioning and coordination systems
- Hall-effect and EM-based sensing
- Power monitoring and protection circuits
- PCB-level circuit design and simulation (KiCad, LTSpice)

---

## Technical Expertise

**Languages**
`C` · `C++` · `Python` · `MATLAB`

**Embedded & Hardware**
`Arduino` · `LoRa` · `GPS Modules` · `Hall-Effect Sensors` · `Analog Circuit Design`

**Design & Simulation**
`KiCad` · `LTSpice` · `SolidWorks`

**Tools**
`Git` · `GitHub` · `VS Code`

---

## Featured Engineering Projects

### LoRa-Based Disaster Management Network

**Problem:** In disaster scenarios, cellular and telecom infrastructure is frequently the first thing to fail, cutting off rescue coordination exactly when it's needed most.

**Engineering Solution:** A mesh of LoRa nodes paired with GPS modules and environmental sensors, designed to operate entirely independent of telecom or internet infrastructure.

**Architecture:** Distributed nodes broadcast location and sensor telemetry over LoRa's long-range, low-power radio link; a base station aggregates data for rescue coordination.

**Technologies:** LoRa, GPS, environmental sensors, Arduino

**Engineering Challenges:** Balancing transmission range against power draw on battery-powered nodes, and ensuring message delivery in a lossy RF environment without a reliable ack/retry infrastructure.

**Engineering Decisions:** Chose LoRa over Wi-Fi/BLE specifically for its range-per-milliwatt characteristics, trading bandwidth for reach and infrastructure independence.

**Results:** Functional communication network validated without dependency on any telecom tower or internet connection.

**Repository:** *(add link)*

---

### Magnetic Field Leakage Detector & Energy Harvester

**Problem:** Industrial equipment can leak stray magnetic fields that indicate insulation or shielding faults, but monitoring this typically requires powered, microcontroller-based instrumentation.

**Engineering Solution:** A dual-function analog circuit that both detects stray magnetic field leakage using Hall-effect sensing and harvests ambient EM energy from the same source.

**Architecture:** Fully analog signal path — no microcontroller — using Hall-effect sensors for detection and a rectification/harvesting stage for energy capture.

**Technologies:** Hall-effect sensors, analog circuit design

**Engineering Challenges:** Achieving reliable detection sensitivity while keeping the harvesting stage efficient enough to be useful, without a microcontroller to actively manage either function.

**Engineering Decisions:** Deliberately avoided a microcontroller to keep the design low-cost, low-maintenance, and dependency-free for industrial deployment.

**Results:** Working dual-function circuit suitable as a low-cost industrial monitoring aid.

**Repository:** *(add link)*

---

### Through-Wall Human Detection System

**Problem:** Search-and-rescue and security applications often need to detect human presence behind a wall without direct line of sight.

**Engineering Solution:** A sensing circuit that analyzes variations in transmitted and reflected EM signals to infer presence behind a barrier.

**Technologies:** EM signal analysis, sensing circuits

**Engineering Challenges:** Distinguishing genuine presence-induced signal variation from ambient RF noise using analog circuitry alone.

**Results:** Functional presence-detection circuit for search-and-rescue and security use cases.

**Repository:** *(add link)*

---

### Overload Protection System

**Problem:** Electrical loads exceeding safe thresholds can cause overheating and component failure if not caught in time.

**Engineering Solution:** A current-monitoring circuit that continuously tracks load and triggers protective cutoff when thresholds are exceeded.

**Technologies:** Power electronics, current monitoring

**Results:** Automatic protection against overload conditions, reducing risk of thermal damage.

**Repository:** *(add link)*

---

### Analog Transmitter & Receiver Pair

**Problem:** Understanding communication systems requires hands-on implementation of the full modulation-transmission-reception chain, not just theory.

**Engineering Solution:** A complete analog transmit-receive pair demonstrating modulation, propagation, amplification, and reception.

**Technologies:** Analog circuits, modulation, RF

**Results:** Working end-to-end analog communication link.

**Repository:** *(add link)*

---

### Smart Shoes for the Visually Impaired

**Problem:** Visually impaired users need low-cost, immediate feedback about obstacles in their path.

**Engineering Solution:** Footwear-integrated obstacle detection with real-time feedback to the wearer.

**Technologies:** Obstacle detection, embedded sensing, assistive hardware

**Results:** Functional, low-cost accessibility prototype.

**Repository:** *(add link)*

---

## Engineering Achievements

- SIH (Smart India Hackathon) — cleared Round 1, advanced to Round 2
- Runner-up, Tenkasi Hackathon
- Finalist, SDG Hackathon and Mumbai Hackathon
- CGPA 9.5/10 through 3rd semester, B.E. Electronics & Communication Engineering, Madras Institute of Technology, Anna University

---

## Engineering Principles

- Reliability first — a circuit that works once means nothing
- Debug before optimizing
- Prefer simple, dependency-free solutions where they hold up
- Design for the failure mode, not just the happy path
- Document the "why" behind a design choice, not just the "what"

---

## Current Engineering Interests

- Embedded Linux fundamentals
- FreeRTOS and real-time scheduling
- TCP/IP and networking fundamentals
- STM32 / ESP32 development
- Device drivers and hardware bring-up
- PCB fabrication workflow (KiCad → manufacture)

---

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hari2128-cell&show_icons=true&theme=github_dark&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hari2128-cell&layout=compact&theme=github_dark&hide_border=true"/>

</div>

---

## Contact

[LinkedIn](https://www.linkedin.com/in/hari-sakthivel-2532a1384) · [GitHub](https://github.com/hari2128-cell) · [Email](mailto:harisakthivel2128@gmail.com)
