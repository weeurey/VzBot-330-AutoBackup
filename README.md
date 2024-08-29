# VZ-250 Klipper Backup Repository 💾

This repository contains the firmware backup for the VzBot 330, serial number Vz-250.

## Specifications

- **Kinematics:** CoreXY, AWD, Dual-Z, CANBus Toolhead
- **Build Plate:** 330x330 mm (with slight Y-axis reduction due to AWD), AC powered with SSR and thermal fuse protection
- **Motherboard:** BigTreeTech KRAKEN 1.0 with BigTreeTech EBB36v1.2 CAN Toolhead Board and BigTreeTech MMB (USB) (TrackRack MCU)
- **Klipper Host:** Raspberry Pi 5 with official active cooler case (4GB RAM, release version)
- **Klipper Version:** v0.12.0-274
- **Hotend:** Goliath Air (full length) with 0.5 Bondtech CHT Nozzle
- **Extruder:** VzHextrudor with Toolhead Entry and Hotend Entry filament sensors (configured for TradRack MMU)
- **Cooling Fan:** Mellow CPAP with 24V hotend fan
- **Automatic Bed Leveling (ABL):** Cartographer Probe in CAN mode with Carto Survey/Touch enabled
- **Movement Motors:** LDO 2804 running on 48V via onboard 5160 drivers
- **Extruder Motor:** Moons 8T
- **Motor Voltage:** 48V

## Multi-Material Unit (MMU)

**TradRack by Annex Designs** with 12 lanes, featuring the following modifications:

- **Happy Hare Software**
- Pregate sensors on 6 of the 12 lanes
- BinkyEncoder with Binky PCB 1.04
- Enraged Rabbit Filament Cutter
- Extruder Entry Sensor
- Toolhead Entry Sensor

## Vanity Accessories

- **Camera:** ELP USB Camera (currently disabled due to compatibility issues with Crowsnest and Raspberry Pi 5)
- **LEDs:** 2x VzLights RGB (Vector 3D) - Disabled due to quality issues (not recommended)
- **Touch Screen:** 7" Elecrow Touch Screen for KlipperScreen (HappyHare Edition)

## Setup Guide

To set up a similar autobackup system, please refer to the [klipper-backup](https://github.com/Staubgeborener/klipper-backup) project, which provides an excellent guide.
