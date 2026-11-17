<div align="center">

# Scratch-Built ArduPilot RC Plane

**A foam-board fixed-wing UAV built from scratch and flown on ArduPilot: SpeedyBee F405 Wing flight controller, GPS, 433 MHz telemetry and Mission Planner. Full parameter file and a real flight log included.**

![ArduPilot](https://img.shields.io/badge/ArduPilot-Plane-0B8ED8?style=for-the-badge&logo=ardupilot&logoColor=white)
![FC](https://img.shields.io/badge/SpeedyBee-F405%20Wing-f59e0b?style=for-the-badge)
![Flight log](https://img.shields.io/badge/flight%20log-included-22c55e?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge)

<img src="docs/images/ground-station-setup.jpeg" width="80%" alt="The plane with the RadioMaster transmitter and Mission Planner ground station"/>

</div>

---

## The build

A hand-built foam-board airframe (high wing, conventional tail) turned into a GPS-capable UAV. Everything here (the parameters and the DataFlash log) is real data from this aircraft, so you can reproduce the setup or learn how to read ArduPilot logs.

<table>
<tr>
<td width="50%"><img src="docs/images/top-view.jpeg" alt="Top view of the airframe"/><br/><sub>Airframe, top view</sub></td>
<td width="50%"><img src="docs/images/plane-and-pilot.jpeg" alt="Builder holding the plane and transmitter at the field"/><br/><sub>At the field</sub></td>
</tr>
<tr>
<td width="50%"><img src="docs/images/avionics-bay.jpeg" alt="Avionics bay: FC, ESC, GPS and telemetry radio"/><br/><sub>Avionics bay: FC, ESC, GPS, 433 MHz telemetry radio</sub></td>
<td width="50%"><img src="docs/images/field-tuning.jpeg" alt="Tuning parameters at the field"/><br/><sub>Field tuning in Mission Planner</sub></td>
</tr>
</table>

## Hardware

| Part | Details |
|---|---|
| Flight controller | **SpeedyBee F405 Wing** running **ArduPilot Plane** |
| Radio | **RadioMaster** transmitter, with mode switching on a switch |
| GPS | **Ready To Sky** GPS module (with compass) |
| Telemetry | **433 MHz** telemetry radio pair to the ground station |
| Propulsion | **1000 KV** brushless motor, ESC, 2-blade prop |
| Airframe | Scratch-built foam board, with carbon spars and bolt-on wings |
| Ground station | Mission Planner on a laptop |

## What's in the repo

| File | What it's for |
|---|---|
| [`ardupilot/log_plane.param`](ardupilot/log_plane.param) | The full ArduPilot parameter set for this airframe. Load it in Mission Planner via **Config → Full Parameter List → Load from file**. |
| [`logs/2025-12-09_17-05-20.bin`](logs/2025-12-09_17-05-20.bin) | A DataFlash flight log. Open it in Mission Planner (**Ctrl+F → Review a Log**) or in [UAV Log Viewer](https://plot.ardupilot.org/). |
| `docs/images/` | Build photos |

## What I did

- Designed and built the airframe
- Integrated the FC, GPS, telemetry and power system
- Calibrated the radio and mapped flight modes
- Configured and tuned ArduPilot parameters
- Ran ground tests and verified everything in Mission Planner
- Logged flight data for analysis

## Next steps

- [ ] Vibration isolation and cleaner cable management
- [ ] Failsafe tuning (RC loss, GPS loss, low battery)
- [ ] Autonomous mission tests: AUTO, RTL, LOITER
- [ ] Flight video + log analysis write-up

## Safety

Fly within local regulations, away from people, with a working failsafe. Bench-test with the propeller removed.

## License

[MIT](LICENSE) © Prateek Sarkar

<div align="center">

**First ArduPilot plane? Grab the params, and leave a ⭐ if they helped.**

</div>
