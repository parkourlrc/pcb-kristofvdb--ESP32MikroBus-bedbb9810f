# ESP32MikroBus

Minimal ESP32C6 project with Mikrobus and Qwiic header 

I needed a minimal ESP32 project with MikroBus.
Since I couldn't find any, I decided to create it myself.

## Current state:
Prototype v1.0 tested with I2C/SPI.
Works out of the box with **ESPHome** of the main development branch(2025.1.0-dev). 
An example yaml was added, that works with RTD Click, for sensing a PT100 temperature sensor.

Prototype v1.1 created and underway for testing
- Revised the power path
- Qwiic header corrected.
- Some components adjusted
- Logo conform spec

If you are interested in obtaining a module, let me know, I have ordered more than I needed.
Visual rendering and pictures can be found in the pictures folder.

Many thanks to the other folks that also made their design open source. That helped this project a lot. If you are looking for an ESP32 board with a POE interface, then have a look at the [Espoir board](https://github.com/Connaxio/espoir).

