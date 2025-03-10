# Voron

Stuff, [Build-Log](BuildLog.md) and Config for my Voron 2.4

## Components

- Raspberry Pi 3b
- Octopus Pro v1.1
- EBB SB2240 CAN
- Shelly Plus 1PM
- E3D V6 Hotend

## Wiring

<img src="wiring.png" width="50%" height="50%">

## Notes

- With the Octopus Pro board a 5V PSU is not necessary
- X and Y endstops are connected to the CAN-Board in the Stealthburner
- The driver for Z1 had problems, so it is connected do a different driver
- The Raspberry is connected with UART and USB to the Octopus, but only USB is used

## Modifications

- Additional Thermistor to measure the case temperature
- CAN-Board on the Stealthburner
- Shelly Switch between Power Switch and PSU for Auto-Shutdown via Home Assistant
- [RocknRoll](https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/RockNLol/RockNRoll)

TODO:

- Filament Sensor (Trianglelab Filament Runout Sensor)
- Klicky Probe
- ERCF
- Telegram bot
- Camera
- LED lighting
- Nozzle Brush
- Nevermore Filter
- Clicky Clacky Door
- Kinematic Mountr
- Panel Latches
