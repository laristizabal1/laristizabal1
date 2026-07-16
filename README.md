<div align="center">

# LUIS ARISTIZABAL
### Electrical & Electronic Engineering — Technical Datasheet · Rev. 1.2

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-angel-aristizabal-correa-09015a359/)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luis0415angelco@gmail.com)

</div>

---

## GENERAL DESCRIPTION

Dual-degree student in Electrical Engineering and Electronic Engineering at Universidad de los Andes (Bogotá, Colombia), working across the stack from power electronics instrumentation to distributed control theory. Recent work spans traceable photovoltaic array emulation for DC microgrids, population-game-based coordination for electric vehicle charging benchmarked against model predictive control, and embedded multi-sensor wearables combining IMU-based gesture detection, RF communication, and real-time web telemetry. Projects are consistently built on state-machine control logic and validated against theoretical or centralized-optimum benchmarks rather than left unverified.

---

## FEATURES

- Dual degree: B.Sc. Electrical Engineering + B.Sc. Electronic Engineering
- Design and instrumentation of programmable DC power supplies for microgrids
- Embedded firmware on ESP32/Arduino with state machines and real-time control
- Sensor fusion (IMU, color sensors, wireless telemetry) for robotic platforms

---

## PIN CONFIGURATION — AREAS OF INTEREST

<div align="center">
  <img src="assets/pinout.svg" alt="Pin diagram" width="600"/>
</div>

---

## ELECTRICAL CHARACTERISTICS

| Parameter | Symbol | Condition / Tools | Status |
|---|---|---|---|
| Power Electronics | P_EE | DC-DC converters, DC microgrids | Proficient |
| Embedded Systems | µC | ESP32, Arduino | Proficient |
| Distributed Control / Game Theory | GNE | Population games, MPC, CasADi | Proficient |
| Signal Processing | DSP | Python, MATLAB | Proficient |
| Circuit Design | PCB | KiCad | Basic–Intermediate |
| Technical Documentation | LaTeX | Reports, papers | Proficient |

---

## TYPICAL APPLICATIONS

| Application | Description | Technologies |
|---|---|---|
| [**PV Array Emulator**](https://github.com/laristizabal1/PV-Emulator.git) | Traceable photovoltaic array emulator built around a programmable DC power supply (EA-PS 10060-170): computes the MPP and I-V curve from real solar data (NASA POWER API) via single/two-diode models, drives the source over SCPI, and exposes live measurements through an optional Modbus TCP bridge for SCADA/PLC integration. Validated against real MPPT-inverter and electronic-load hardware | `Power Electronics` `DC Microgrids` `SCPI` `Modbus TCP` `Dash` |
| [**EV-Charging-GT**](https://github.com/laristizabal1/EV-Charging-GT.git) | Distributed EV charging coordination via Generalized Nash Equilibrium population games (PG-GNE), benchmarked against MPC and the centralized optimum (CasADi + IPOPT) | `Population Games` `MPC` `CasADi` `Python` |
| [**MENTORU**](https://github.com/fg-edu-tep/MENTORU.git) | Distributed ESP32-based biometric monitoring system: multiple wearables (smartwatch, glasses, chest strap, GSR sensor) measure physiological and motion signals and broadcast them over a custom ESP-NOW protocol (ESB-P) to a central receiver that exposes live readings as JSON over HTTP | `ESP32` `ESP-NOW` `KiCad` `LVGL` |
| [**limpiaVidrios**](https://github.com/fgutep/limpiaVidrios.git) | Window-cleaning robot governed by a motor state machine; NeoPixel voltage-level indicators, TCS34725 color sensor, MPU6050 IMU for orientation, gamepad control (Bluepad32), and WiFi telemetry. Collaborative project with Felipe Gutiérrez | `ESP32` `State Machines` `MPU6050` `NeoPixel` |
| [**ARGOS3000**](https://github.com/laristizabal1/ARGOS3000.git) | Multi-sensor wearable (ESP32-S3): LDR, PIR, TILT, MQ135, DHT22, with a gesture-triggered emergency protocol and 433 MHz RF communication between devices, plus a real-time embedded web dashboard | `ESP32-S3` `RF 433MHz` `WebServer` |

---

## MEASURED PERFORMANCE

<div align="center">

<img src="profile/stats.svg" alt="GitHub Stats" />

<img src="profile/top-langs.svg" alt="Top Languages" />

</div>

---

## REVISION HISTORY

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-07 | Initial profile release |
| 1.1 | 2026-07 | Added EV-Charging-GT (PG-GNE) and ARGOS3000; new distributed-control characteristic |
| 1.2 | 2026-07 | Unified profile language to English |

<div align="center">

*Linearity of ideas outside the recommended operating range is not guaranteed.*

<img src="https://komarev.com/ghpvc/?username=laristizabal1&label=Profile+Views&color=0e75b6&style=flat-square" alt="profile views" />

</div>
