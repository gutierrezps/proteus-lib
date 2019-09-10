# Proteus Library

This is my personal library for the Labcenter Electronics Proteus Design Suite (ISIS and ARES programs). Files `YZDEVLIB` contain schematic symbols, and `YZPKGLIB` contain PCB packages. Some schematic symbols were copied from the default libraries because I assigned different/aditional footprints for them.

Tested on Proteus 7.8 and 7.10, I'm not sure if they work on Proteus 8.

Feel free to contribute with new symbols and/or packages.

## Installation

* Make sure ISIS and ARES are not running
* Download this repo as zip and extract it
* Copy/move files `*.LIB` and `*.IDX` into `C:\Users\<username>\AppData\Local\VirtualStore\Program Files (x86)\Labcenter Electronics\Proteus 7 Professional\LIBRARY` if this path exists, otherwise into `C:\Program Files (x86)\Labcenter Electronics\Proteus 7 Professional\LIBRARY`.

## Schematic symbols

* 1N4148 - diode
* 24C16 - I2C memory
* ACS712 module - current sensor
* Arduino Nano, Arduino Pro Mini
* AS1582 - voltage regulator
* AU-Y1007-R - USB plug
* BAT20J - schottky diode
* BATT, BATT-12MM, BATT-20MM - battery cell
* BC327, BC337 - BJT transistors
* BUZZER
* CONN-DIL12, DIL14, DIL40
* CONN-SIL1, SIL11, SIL12, SIL15, SIL3, SIL4, SIL5, SIL6, SIL7
* CONN_2x23 (DIL23)
* CRYSTAL
* D1-MINI - Wemos D1 Mini
* DC JACK
* DC-DC - stepdown DC converter
* DIODE-SC
* DS1337 - low power RTC
* ESP-01, ESP-12E - ESP8266 modules
* HLK-PMXXX - Hi-Link AC-DC module (PM01, PM03, PM09, PM012)
* INDUCTOR
* JUMPER
* LED
* LED_RGB
* LLC1 - 4-channel logic level converter module
* LM016L - 16x2 LCD
* LM041L - 16x4 LCD
* MBRA130LT3G - schottky diode
* MOTOR_3PHASE
* POT - potentiometer
* PUSH-BUTTON, PUSH-BUTTON-DP - single and dual pole tactile switches
* RES - resistor
* RJ-45 - "Ethernet" connector
* SW-DPDT, SW-SPDT, SW-SPST - switches
* TINYRTC - RTC module

## Footprints/Packages

* 0605, 0805-DIODE
* ACS712_MODULE
* ARDUINO_NANO, ARDUINO_PRO_MINI
* BATT-12MM, BAT-20MM - coin cell batteries
* BR1/2AAE5P - battery
* BRC-DS-210 - DC power jack
* BUZZER-12MM, BUZZER-M12-300, BUZZER-M9.5-200 - buzzers [diameter]-[pitch]
* CAP-PANASONIC-SMD-D
* CMR200T - crystal
* CONN-DIL12-R, DIL14 - round pads
* CONN-SIL1-R, SIL10, SIL15, SIL3, SIL4, SIL6, SIL7 - round pads
* CONN-SIL11, SIL15, SIL8 - square pads
* CONN40_2X20 (DIL20)
* CONN46_2X23 (DIL23)
* D1-MINI - Wemos D1 Mini module
* ESP-01, ESP-12E, ESP12E-DIP - ESP8266 modules
* GRPB031VWTC-RC, GRPB051VWTC-RC, GRPB061VWTC-RC, GRPB071VWTC-RC - SMD pin headers
* HLK-PMXXX - Hi-Link AC-DC module (PM01, PM03, PM09, PM012)
* LCD_1602B-E, LCD-1602G, LCD_JHD539 - alphanumeric LCD displays
* LED_3MM, LED_RGB
* LLC1 - 4-channel logic level converter module
* LPPB031NFFN-RC, LPPB051NFFN-RC, LPPB061NFFN-RC, LPPB121NFFN-RC - pin headers female
* MP1584-MODULE - stepdown DC converter
* RES10 - upright resistor
* RES30 - resistor
* RJ-45 - "Ethernet" female connector
* SMA-2, SOD-80 - diode
* SW-DPDT-7X7 - 7x7 mm switch
* SW-KFT-8.5 - 8.5mm switch
* SW-MICRO-SPDT - micro switch (lever)
* SW-PUSH-2T, SW-PUSH-2T-RIGHT - 2-pin tactile switches
* SW-PUSH-4T - 4-pin tactile switches
* TINYRTC - RTC module
* TO263-5 - 5-pin SMD package (used by the AS1582)
* XTAL-SM - crystal
* YH-55-05 - RJ45 "ethernet" female connector

---

2018 - Gutierrez PS