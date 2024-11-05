<p align="center" style = "font-size:48px;" >SCEPad</p>

<div align="center"

[![Status](https://img.shields.io/badge/Status-Active-green)]()
[![Team](https://img.shields.io/badge/Team-Hardware-blue)]()
[![Term](https://img.shields.io/badge/Fall_2023-purple)]()
[![QMK](https://img.shields.io/badge/QMK-gray?logo=qmk)]()
[![KiCAD](https://img.shields.io/badge/KiCAD-gray?logo=kicad)]()

</div>

## General Description 
The SCE Pad is a instructional tool used during our soldering workshop series.

## Table of Contents
- Bill of Materials
- Firmware Flashing
- Assembly Instructions 

## Bill of Materials
| Qty | Item                                  | Notes
| ---- | ---- | ---- |
| 1   | Arduino Pro Micro (ATmega32u4)        | Alternatively you can use the [Elite-C](https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4) or [Nice!Nano](https://nicekeyboards.com/nice-nano/)|
| 18  | Cherry MX compatible swtiches         | |
| 18  | SOD-123 1N4148/1N4148W diodes         | |
| 18  | Kailh PCB sockets CPG151101S11        | |
| 9   | WS2812B RGB LEDs                      | |
| 9   | SMD 0805 100nF capacitors             | |
| 1   | I2C 0.91" 128\*32 OLED Display Module | The ones using SSD1306 driver IC over I2C |
| 1   | 6mm\*6mm button switch                | |
| 1   | SCEPad PCB                            | Available in SCE Club Room (ENG294) |
| 5   | M3 screws                             | |

## Firmware Flashing

Requirements
- [QMK Toolbox](https://github.com/qmk/qmk_toolbox)

After installing QMK toolbox, assuming you are using the default ProMicro controller, plug the device into your computer and you should see it show up as a new device in the console. Make sure the MCU selected is an ATmega32U4. Auto-flash is useful here but its preference. 

Select your hex-file and flash your microcontroller. 

