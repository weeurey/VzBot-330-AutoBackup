# VZ-250 Klipper Backup 💾 
This is the firmware backup repostory for a VzBot 330 with serial Vz-250.

# Specs
Kinematics: CoreXY, AWD, Dual-Z, CANBus Toolhead

Build Plate: 330x330 (small amount of Y loss due to AWD) AC powered with SSR + thermal fuse protection

Motherboard: BigTreeTech KRAKEN 1.0 W/ BigTreeTech EBB36v1.2 CAN Toolhead board + BigTreeTech MMB(USB)(Trackrack MCU)

MMU: Tradrack (Currenty disabled Until Binky+ERFC Mod is installed.)

Klipper Host: Raspbery Pi 5, Official active cooler case (4GB Ram, release version)

Klipper Version: v0.12.0-274 

Hotend: Goliath Air (Full length) with .5 Bondtech CHT Nozzle

Extruder: VzHextrudor w/ Toolhead Entry and Hotend Entry filament sensors. (For TradRack MMU)

Cooling Fan: Mellow CPAP + 24v Hotend fan

ABL: Cartogrophger Probe in CAN mode with Carto Survey/Touch enabled.

Movement Motors: LDO 2804 running on 48v via onboard 5160 drivers

Extruder Motor: Moons 8T

Motor Voltage: 48V


Camera: ELP USB Camera(currently disabled due to crowsnewst x RPi5 issues)

LEDs: 2x VzLights RGB (Vector 3D, Disabled due to poor QA, I dont reccomend purchasing these.)






To set up a similar autobackup system please see the fantastic [klipper-backup](https://github.com/Staubgeborener/klipper-backup) project.
