# BMS 5s (12 V)
Battery management system for up to 5 Li-ion cells based on bq76920 IC from Texas Instruments

## Features

- 3 to 5 Li-ion cells (e.g. LiFePO4)
- Power circuit on separate board (see Switch-N-Sense repository)
- Balancing current approx. 150 mA
- STM32F072 ARM Cortex M0 microcontroller
- Built-in CAN communication interface and UEXT extension connector

## Housing

The BMS should fit into a Hammond Mfg 1591XXBFL housing as shown in below picture. The picture shows the BMS controller PCB with the new Switch-N-Sense PCB stacked on top of it:

![Libre Solar BMS 5s including housing](FreeCAD_Housing.PNG)

## History

- There is [another version of the BMS](https://github.com/LibreSolar/BMS48V)  supporting more cells and developed in Eagle CAD. This one is the first of the new BMS generation developed in KiCad. An updated version of the versions with higher number of cells will come soon.
