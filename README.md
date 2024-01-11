# SO-DIMM DDR5 Tester

Copyright (c) 2023-2024 [Antmicro](https://antmicro.com)

![](img/sodimm-ddr5-tester-vis.png)

## Overview

This project contains open hardware KiCad design files for an experimental platform built around the Xilinx Kintex-7 FPGA, which can be used to interface with SO-DIMM DDR5 RAM modules.

## Project structure

The main repository directory contains KiCad PCB project files, a LICENSE and README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README

## Key features

* Kintex-7 FPGA (XC7K160T-FFG676)
* SO-DIMM DDR5 slot
* HDMI output connector
* Ethernet RJ45 connector with 1GbE transceiver
* USB-C debug connector with FT4232HQ FTDI USB controller
* JTAG
* microSD card slot
* 16 MBytes S25FL128S QSPI FLASH memory
* S27KL0641 HyperRAM
* External 7-12V DC power input

## License

This project is published under the [Apache-2.0](LICENSE) license.
