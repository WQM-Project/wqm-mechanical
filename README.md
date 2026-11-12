# Water Quality Monitoring - Mechanical Design 

> Hardware and mechanical engineering files for a remote-controlled (RC) catamaran designed for real-time river water quality monitoring.

---

## Overview
This repository contains all mechanical documentation, manufacturing exports, and 3D CAD models for the water quality monitoring vessel. The physical platform is designed to safely carry the active sensor payload (pH, DO with 7.5% KCl membrane cap, TDS, ORP, DS18B20 water temperature, internal BMP280 barometer, and BNO085 IMU, plus reserved mounts for Turbidity/EC), an STM32 Nucleo-F722ZE microcontroller enclosure, the onboard ESP32 + SIM7600 4G LTE & GNSS gateway (supplying cellular backhaul and GPS coordinates without a separate LoRa shore station), and LiFePO4/lithium batteries through variable river conditions.

---

##  Repository Structure

```text
/wqm-mechanical/
│          
├── Exports/                 
│   └── STL/                 # 3D Printable files (Sensor mounts, propellers, hull sections)
├── Design_Reviews/          # Engineering reports and consultation notes
└── README.md                # This document
