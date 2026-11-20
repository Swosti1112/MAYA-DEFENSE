# MAYA SENTINEL-X

### Uninterrupted Soldier–HQ Communication under Cyber & Physical Threats

MAYA SENTINEL-X is a prototype soldier-to-headquarters communication and monitoring system designed to maintain communication and provide situational awareness under challenging field conditions.

The system combines LoRa-based wireless communication, human presence detection, visual monitoring and local alert mechanisms.

## Project Overview

The project aims to establish a reliable communication link between a field unit and a headquarters (HQ) unit while monitoring potential physical threats.

## Hardware Components

- 2 × Heltec WiFi LoRa 32 V3
- 1 × LD2410C Human Presence Radar
- 1 × ESP32-CAM-S (OV2640 + PSRAM)
- 2 × Arduino Uno
- LEDs
- Buzzer

## Key Features

- Long-range communication using LoRa.
- Human presence detection using LD2410C radar.
- Visual monitoring using ESP32-CAM.
- Local alert generation using LEDs and buzzer.
- Field-to-HQ event transmission.
- Local monitoring and event logging.

## System Architecture

The system consists of two primary units:

**1. Field Unit**
- Detects human presence.
- Processes sensor information.
- Transmits events through LoRa.

**2. Headquarters Unit**
- Receives field information.
- Processes incoming events.
- Generates alerts.
- Provides local monitoring.

## Technology Stack

| Category | Technology |
|---|---|
| Embedded Systems | ESP32, Arduino |
| Communication | LoRa |
| Programming | C++, Python |
| Backend | Flask |
| Database | SQLite |
| Hardware Detection | LD2410C |
| Visual Monitoring | ESP32-CAM |

## Repository Structure

- `firmware/` – Embedded firmware for hardware components.
- `dashboard/` – Local monitoring dashboard.
- `config/` – Configuration templates.
- `docs/` – Technical documentation.
- `tests/` – Software testing.

## Project Constraints

- No GPS dependency.
- No cloud dependency.
- No The Things Network (TTN).
- Local communication and processing.

## Development Status

This repository contains the reconstructed project baseline. Hardware integration, communication reliability, security mechanisms and end-to-end testing are being developed and validated.

## Team

**Project:** MAYA SENTINEL-X  
**Team:** MAYA MATRIX  
**Project Lead:** Swosti Jena

---

*Building resilient communication systems for challenging environments.*