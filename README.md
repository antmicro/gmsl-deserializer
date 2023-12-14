# GMSL Deserializer Board

Copyright (c) 2023 [Antmicro](https://www.antmicro.com)

![](img/antmicro-gmsl-deserializer-hw_top_photo_black.png)


## Overview

This project contains open hardware design files for the Antmicro GMSL Deserializer Board, capable of translating up to 4 GMSL signals into 2x 4-lane MIPI CSI-2 interface. The board is designed to connect to a baseboard, eg [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard), via 50pin FFC.

The design files were prepared in KiCad 6.x.


## Key features

* Four GMSL ports
* MIPI CSI-2 interface on 50-pin connectors
* DC Power connector


## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README
* `doc` - contains schematics in pdf form
* `assets` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com).

The board exposes MIPI CSI-2 interfaces using unified 50-pin connectors that are electrically compatible with a variety of boards created by Antmicro:

* [Jetson Nano Baseboard](https://github.com/antmicro/jetson-nano-baseboard)
* [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard)
* [SA800U (Snapdragon 845) Baseboard](https://github.com/antmicro/snapdragon-845-baseboard)
* [SC606T (Snapdragon 625) Baseboard](https://github.com/antmicro/snapdragon-625-baseboard)
* [Kria K26 Devboard](https://github.com/antmicro/kria-k26-devboard)


## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
