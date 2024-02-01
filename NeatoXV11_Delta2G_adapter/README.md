# Adapter PCB for LDS02RR laser distance scanner

Connect Neato XV-11/Botvac or Delta-2G LDS to Arduino to capture laser distance data.

This PCB implements PWM motor control for Neato XV/Botvac and Delta-2G LDS. Find
sample Arduino ESP32 firmware code [here](https://github.com/kaiaai/LDS02RR_ESP32)
and Arduino LDS library [here](https://github.com/kaiaai/LDS).

## Files
- [schematic PDF](output/NeatoXV11_Delta2G_adapter_schematic.pdf)
- [BoM .CSV](output/NeatoXV11_Delta2G_adapter_BOM.csv), [BoM .XML](output/NeatoXV11_Delta2G_adapter_BOM.xml)
- [Gerber .ZIP](output/NeatoXV11_Delta2G_adapter_gerber.zip)
- [3D model .STEP](output/NeatoXV11_Delta2G_adapter.step)
- KiCAD schematic, layout - in this folder

## Top
![PCB 3D view from top](output/NeatoXV11_Delta2G_adapter_top.jpg)

## Bottom
![PCB 3D view from top](output/NeatoXV11_Delta2G_adapter_bottom.jpg)

# Change log

## v0.3.0
- added Delta-2G connector

## v0.2.0
- added a bypass capacitor

## v0.1.0
- initial prototype
- optional LM2596 voltage regulator module provides 3.3V to motor