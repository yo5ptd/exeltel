# exeltel
exeltel cartridge for 27c256 eprom

## Introduction

exeltel exl 100, i had no basic catridge to test it, so i made one. 

## Hardware Documentation
Idea is to make it without vias, so i can use my CNC to mill PCB. I just added a pullup resistor and a cut jumper, so i can use 27c128 or 27c64 eproms too (not tested yet). Just make sure that when inserted, the eprom faces down (bottom of PCB marked with the letter B is facing up.

### Schematic and PCB Layout

[Schematic](sch.pdf)

[PCB Layout](pcb.pdf)

[Image](exeltel.png)

### Bill of Materials

Component Type | Reference | Description                             | Quantity | Possible Sources and Notes
-------------- | --------- | --------------------------------------- | -------- | --------------------------
PCB            |           | exeltel     	                           | 1        | mill it on your CNC
Capacitor      | C1        | 0.1 uF ceramic                          | 1        | regular ceramif filter cap
Resistor       | R1 	     | 10 k pullup                             | 1        | optional for  27c128 or 27c64

I was able to run exelbasic. I used ROM's from https://archive.org/details/Exelvision_EXL_100_TOSEC_2012_04_23
