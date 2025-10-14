# Voron

Stuff, [Build-Log](BuildLog.md) and Config for my Voron 2.4

## Components

- Raspberry Pi 3b
- Mainboard: [Octopus Pro v1.1](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446)
- Hotend: [Phaetus Dragon HF](https://www.phaetus.com/products/dragon-hotend-hf)

## Modifications to the Default Voron

- Additional Thermistor to measure the case temperature
- Stealthburner CAN: [EBB SB2240 CAN](https://biqu.equipment/products/bigtreetech-ebb-sb2209-can-v1-0?variant=40214282731618)
- Shelly Plus 1PM Switch between Power Switch and PSU for Auto-Shutdown via Home Assistant
- [RocknRoll](https://github.com/VoronDesign/VoronUsers/tree/main/printer_mods/RockNLol/RockNRoll)
- [Voron Tap CNC](https://www.chaoticlab.com/products/cnc-voron-tap?variant=40494842675298)
- [Triangle Labs Filament Sensor](https://www.trianglelab.net/products/sensors?VariantsId=10607)
- [BTT Eddy Probe](https://biqu.equipment/products/bigtreetech-eddy)
- [Nozzle Brush mit Bucket](https://www.printables.com/model/201999-nozzle-scrubber-with-a-little-bucket-for-voron-24?lang=de)
- [Panel Latches](https://github.com/richardjm/voron-parts/tree/main/voron-2.4/FilamentLatch)
- [AngryCam](https://mods.vorondesign.com/details/RYpQW53mtem8Nj1JKqiSQ) (Primary Cam)
- [CamHolder](https://www.printables.com/model/673803-5mp-cam-usb-for-76-degree-auto-fixed-focus-usb-cam) (Secondary Cam)
- [PEI Stop](https://mods.vorondesign.com/details/HPcfxCUYAw8jwTTRJOf9IA)

## Wiring

<img src="wiring.png" width="50%" height="50%">

## Notes

- With the Octopus Pro board a 5V PSU is not necessary
- X and Y endstops are connected to the CAN-Board in the Stealthburner
- The driver for Z1 had problems, so it is connected do a different driver
- The Raspberry is connected with UART and USB to the Octopus, but only USB is used

## TODO

- [ ] SW control of the exhaust fan
- [ ] SW control of the case fans
- [ ] Emergency Off
- [ ] Nevermore Filter / [Nevermore Micro](https://github.com/nevermore3d/Nevermore_Micro)
- [ ] [Clicky Clacky Door](https://github.com/tanaes/whopping_Voron_mods/blob/main/clickyclacky_door%2FREADME.md)
- [ ] Kinematic Mounts
- [ ] Beefy Front Idlers
- [ ] [Display Mount](https://www.printables.com/model/926845-btt-hdmi5-v12-display-mount-voron)
- [ ] [Kmomi 2 Remote Control](https://www.printables.com/model/789391-watchmi-the-knomi-2-remote-controller-for-klipper)
- [ ] [HULA Feet](https://github.com/thrutheframe/HULA_Voron)
- [ ] [FilamATrix](https://github.com/thunderkeys/FilamAtrix)
- [ ] [BallJoint](https://github.com/bwilliams9611/ERCF_BallJoint_Passthrough)
- [ ] [Enraged Rabbit Carrot Feeder](https://github.com/Carrot-collective/ERCF_v2)
- [ ] [Pika Filament Buffer](https://github.com/geoffrey-young/pika-filament-buffer/tree/main)
