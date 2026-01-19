# RC Plane UAV Project ✈️ (SpeedyBee Wing 405 + RadioMaster + GPS)

This repository documents my **fixed-wing RC plane build and integration** using a **SpeedyBee Wing 405** flight controller,
GPS module, BLDC propulsion system and RadioMaster transmitter setup.

The goal of this project is to build a stable and expandable UAV platform for **manual flight + autopilot-supported navigation and testing**.

---

## ✅ Hardware Used

### Flight Controller
- **SpeedyBee Wing 405** (ArduPilot compatible)

### RC System
- **RadioMaster transmitter** (manual control + mode switching)

### Propulsion
- **BLDC motor: 1000KV**
- ESC + propeller (fixed-wing configuration)

### Navigation
- **GPS module** (positioning + navigation ready)

---

## 🔧 What I did in this project
- ✅ Designed and assembled the fixed-wing airframe
- ✅ Integrated flight controller + GPS + power system
- ✅ RC calibration and control mapping
- ✅ ArduPilot parameter setup and configuration
- ✅ Ground testing + mission planner verification
- ✅ Collected flight log data for analysis

---

## 🖼️ Project Images

### RC Plane (Top View)
![RC Plane Top View](docs/images/rc-plane-top-view.jpeg)

### Setup (Flight Controller + Mission Planner + RadioMaster)
![RC Plane Setup](docs/images/rc-plane-setup-radiomaster.jpeg)

---

## 🧠 ArduPilot Configuration
This repo includes my configuration and tuning reference file:

- `ardupilot/params/log_plane.param`

This makes the setup reproducible for future iterations and debugging.

---

## 📊 Flight Logs
Flight testing logs are saved in:

- `logs/2025-12-09_17-05-20.bin`

These logs can be opened in **Mission Planner** for performance verification and debugging.

---

## 📂 Repository Structure
- `docs/` → photos + build notes
- `ardupilot/params/` → parameter files (`.param`)
- `logs/` → DataFlash logs (`.bin`)

---

## 🚀 Future Improvements (Planned)
- Improve airframe cable management and vibration isolation
- Add telemetry link for live monitoring
- Add better failsafe tuning (RC + GPS)
- Autonomous modes testing (AUTO / RTL / LOITER as supported)

---

## ⚠️ Disclaimer
This project is intended for learning and experimentation.
Always follow safety guidelines while testing UAVs.

---

## 👤 Author
**Prateek Sarkar**  
UAV Systems • Embedded Electronics • PCB Design • Robotics
