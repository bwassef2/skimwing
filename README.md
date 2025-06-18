# Project SkimWing — Terrain-Following Autonomous Drone

Welcome to the repo for an autonomous fixed-wing drone that performs real-time terrain following using onboard sensors, adaptive feedback control, and full-stack simulation. Built for academic, research, and aerospace GNC applications, this project is both simulated and physically validated — all on a sub-$250 budget.

---

## Overview

SkimWing is a terrain-following fixed-wing drone designed and built by Brad Wassef, an aerospace engineering student at UIUC, to demonstrate real-world Guidance, Navigation, and Control (GNC) capabilities. The system uses a downward-facing rangefinder and onboard estimation to track terrain contours in real time while maintaining stable, low-altitude flight. The project combines full PX4/Gazebo simulation, custom controller design, and physical flight testing on a student budget.

---

## Features

- Real-time terrain-following using downward-facing rangefinder
- LQR and PID-based altitude controllers
- PX4 SITL + Gazebo simulation with synthetic terrain
- Full physical prototype with Pixhawk 4 Mini
- Flight log analysis, controller tuning, and performance metrics

---

## Technologies Used

- PX4 Autopilot + QGroundControl
- Gazebo for simulation
- Python + Jupyter for flight log analysis
- MATLAB/Simulink for control prototyping
- TF-Luna rangefinder + GPS + Pixhawk 4 Mini
- Runs entirely on a base M2 MacBook Air

---

## Repo Structure

skimwing/
├── hardware/               # BOM, wiring diagrams, physical build photos
├── simulation/             # PX4 SITL configs, Gazebo world files
├── controller_design/      # LQR derivation, Simulink/Python tuning
├── flight_logs/            # Real-world data logs + performance plots
├── notebooks/              # Estimation and control analysis in Jupyter
├── docs/                   # Final report, slides, diagrams
└── images/                 # Plots, terrain tracking visuals, build photos


---

## Performance Metrics

| Metric                     | Goal        | Achieved |
|---------------------------|-------------|----------|
| RMS Altitude Error        | < 2.0 m     | TBD      |
| Control Signal Smoothness | High        | TBD      |
| Real-Time Processing      | Onboard     | Yes      |
| Flight Stability          | Robust      | Yes      |

---

## Demo Video

Coming soon: [YouTube link or embedded video]

---

## License

MIT License — free to fork, remix, and use with attribution.

---

## Contact

Brad Wassef • Aerospace Engineering @ UIUC  
[LinkedIn](https://www.linkedin.com/in/bwassef/) • bwassef2@illinois.edu

