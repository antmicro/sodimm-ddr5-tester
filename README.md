# Data Center RDIMM DDR4 Tester

Copyright (c) 2021-2023 [Antmicro](https://antmicro.com)

[![DDR4 RDIMM tester board @ opensource.antmicro.com](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/data-center-rdimm-ddr4-tester)

![DDR4 RDIMM tester board](img/data-center-rdimm-ddr4-tester-1.2.0.png)

## Overview

This repository contains open hardware KiCad design files for an experimental platform built around the Xilinx Kintex-7 FPGA which can be used to interface with RDIMM DDR4 RAM modules used in data centers.

This hardware platform is used in Antmicro's and Google's [Rowhammer testing framework](https://github.com/antmicro/rowhammer-tester) which can be used to perform (and potentially mitigate) Rowhammer attacks on DRAM memories. You can learn more about Rowhammer and our work towards mitigating it in a Google Open Source blog note [describing a related platform](https://opensource.googleblog.com/2021/11/Open%20source%20DDR%20controller%20framework%20for%20mitigating%20Rowhammer.html).
The usage instructions for this board are also provided in the [Rowhammer testing framework documentation](https://antmicro.github.io/rowhammer-tester/). 

## Repository structure

The main repository directory contains KiCad PCB project files, a LICENSE and README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README

## Key Features

* Kintex-7 FPGA (XC7K160T-FFG676)
* DDR4 RDIMM connector with hotswap
* HDMI output connector
* Ethernet RJ45 connector with 1GbE transciever
* USB-C debug connector with FT4232HQ FTDI USB controller
* JTAG
* microSD card slot
* 16 MBytes S25FL128S QSPI FLASH memory
* S27KL0641 HyperRAM
* External 7-12V DC power input
* PoE++
* Power consumption monitoring
* 5 user LEDs
* Optional FMC HPC expansion connector

## Block diagram

![Data Center RDIMM DDR4 Tester board diagram](doc/Data-Center-RDIMM-DDR4-Tester-block-diagram.png)

## License

This project is published under the [Apache-2.0](LICENSE) license.
