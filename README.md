# SunScout: Smart Solar Tracking System

Low-cost IoT solar tracker built with an ESP32. Two LDR light sensors drive an SG90 servo that turns a solar panel toward the strongest light, and a web dashboard shows everything in real time.

University project (LCE2 Projet Fédéré, FST, Université Tunis El Manar, 2025/2026), supervised by Faouzi Moussa.

## Features

- Single-axis automatic sun tracking (LDR left/right, tolerance threshold to avoid jitter)
- Embedded web server on the ESP32 with a REST API (`/data`, JSON)
- Real-time dashboard (HTML/CSS/JavaScript): sensor values, panel angle, live chart, movement history, day/night indicator, tracking efficiency
- Solar panel 5V + TP4056 charger + 18650 battery for energy storage
- Simulated on Wokwi, then built on real hardware

## Hardware

ESP32, 2x LDR, SG90 servo, 5V solar panel, TP4056 module, 18650 battery, LED + 220 ohm resistor

## Software

Arduino IDE (ESP32 firmware), VS Code (dashboard), Wokwi (simulation), Jira/Scrum (3 sprints)

## Files

- `RAPPORT.pdf`: full project report (French)
- `SLIDES.pdf`: presentation slides
- `RenduFinal.pdf`: final submission
- `LCE2.mp4`: demo video

## Team

Farah Benarbi, Amani Arouri, Mohamed El Mehdi Aouni, Baraa Benarfi, Rym Jlidi
