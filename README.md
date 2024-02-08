# SO-DIMM DDR5 Tester

Copyright (c) 2023-2024 [Antmicro](https://antmicro.com)

[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/sodimm-ddr5-tester/)
[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Hardware%20Portal-332d37?style=flat-square)](https://openhardware.antmicro.com/boards/sodimm-ddr5-tester/?tab=features)
![](img/so-dimm-ddr5-tester-rev.1.1.0-photo.jpg)

## Overview

This project contains open hardware KiCad design files for an experimental platform built around the Xilinx Kintex-7 FPGA, which can be used to interface with SO-DIMM DDR5 RAM modules.

## Project structure

The main repository directory contains KiCad PCB project files, a LICENSE and README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README
* `doc` - contains pdf schematics
* `assets` - contains visual assets for showcasing this design on [Antmicro Hardware Portal](https://openhardware.antmicro.com)

## Key features

* Kintex-7 FPGA (XC7K160T-FFG676)
* SO-DIMM DDR5 memory slot
* HDMI output connector
* Ethernet RJ45 connector with 1GbE transceiver
* USB-C debug connector with FT4232HQ FTDI USB controller
* JTAG connector
* PCIe 4x Edge connector
* microSD card slot
* 16 MBytes S25FL128S QSPI FLASH memory
* IS66WVH16M8DBLL HyperRAM
* External 7-15V DC power input

## License

This project is published under the [Apache-2.0](LICENSE) license.
