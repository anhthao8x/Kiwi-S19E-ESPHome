# Kiwi S19E ESPHome

ESPHome firmware for Kiwi S19E WiFi Smart Socket.

## Features

- Relay control
- Physical switch
- Factory reset button
- WiFi fallback AP
- Home Assistant API

## Hardware

| Component | GPIO |
|------------|-------|
| Relay | GPIO12 |
| Switch | GPIO5 |
| Button | GPIO13 |
| LED | GPIO4 |

![Sơ đồ chân GPIO Kiwi S19E](images/GPIO.png)

## Installation

1. Install ESPHome
2. Copy `secrets.example.yaml` to `secrets.yaml`
3. Configure WiFi credentials
4. Flash the firmware

## Home Assistant

The device is automatically discovered through the ESPHome integration.
