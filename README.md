# VZ-250 Klipper Backup 💾 
This is the firmware backup repostory for a VzBot 330 with serial Vz-250

#Specs
Kinematics: CoreXY, AWD, Dual-Z
Build Plate: 330x330 (small amount of Y loss due to AWD) AC powered with SSR + thermal fuse protection
Motherboard: BigTreeTech KRAKEN 1.0 + BTT MMB(Trackrack)
MMU: Tradrack (Currenty disabled)
Klipper Host: Raspbery Pi 5 (4gb)
Klipper Version: Version of  v0.12.0-115 that is modified by me to have some extra features to do with low priority secondary MCUs(Cartogropgher) (Mainsail)

Hotend: Goliath with .5 Bondtech CHT Nozzle
Extruder: VzHextrudot
Cooling Fan: Mellow CPAP
ABL: Cartogrophger Probe
Movement Motors: LDO 2804
Extruder Motor: Moons 8T
Motor Voltage: 48V

Camera: ELP USB Camera(currently disabled due to crowsnewst x RPi5 issues_
LEDs: 2x VzLights RGB (Vector 3D)






To set up a similar autobackup system please see [klipper-backup](https://github.com/Staubgeborener/klipper-backup).
