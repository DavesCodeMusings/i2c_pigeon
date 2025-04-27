# I2C Pigeon
Solder in some standard 2.54mm pin headers and attach multiple I2C devices to a single microcontroller bus. Includes 3mm mounting hole for easy enclosure anchoring.

![image](https://github.com/user-attachments/assets/ab25423e-fa1b-4a3c-85cb-1ca2f015f442)

What you will find here are the [KiCad](https://www.kicad.org/) schematic and PCB files for the board you see above. A run of three at [OSHPark](https://oshpark.com) cost me $3.25(US).

The original design criteria was to attach a BH1750 ambient light sensor, SHT30 temperature/humidity sensor, and maybe a small SSH1306 OLED display to a single ESP32 I2C bus using common DuPont jumpers.

Everything here is released to the public domain with no warranty expressed or implied. It's like this: if it breaks, you get to keep both pieces!

> Pigeon mascot adapted from [public domain image at Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Bird_template.svg). Groan-worthy catchphrase is my own, with apologies to [Mo Willems](https://en.wikipedia.org/wiki/Don%27t_Let_the_Pigeon_Drive_the_Bus!).
