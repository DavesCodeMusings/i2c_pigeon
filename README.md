# I2C Pigeon
Solder in some standard 2.54mm pin headers and attach multiple I2C devices to a single microcontroller bus. Includes 3mm mounting hole for easy enclosure anchoring.

![image](https://github.com/user-attachments/assets/ab720a0c-967c-4946-9b83-b9949b7bf42a)

What you will find here are the [KiCad](https://www.kicad.org/) project files for the board you see above (pin header not included.) A run of three at [OSHPark](https://oshpark.com/shared_projects/UAQo7iUX) cost me $3.25(US).

The original design criteria was to allow attaching a BH1750 ambient light sensor, SHT30 temperature/humidity sensor, and maybe a small SSH1306 OLED display to a single ESP32 I2C bus using common DuPont jumpers.

Everything here is released to the public domain with no warranty expressed or implied. It's like this: if it breaks, you get to keep both pieces!

> Pigeon mascot adapted from [public domain image at Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Bird_template.svg). Groan-worthy catchphrase is my own, with apologies to [Mo Willems](https://en.wikipedia.org/wiki/Don%27t_Let_the_Pigeon_Drive_the_Bus!).
