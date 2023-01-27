# Data Center DDR4 Tester Enclosure

Copyright (c) 2022-2023 [Antmicro](https://antmicro.com)

![Data Center DDR4 Tester Enclosure](img/ddr4-tester-enclosure.png)

## Overview

This repository contains open hardware mechanical design design files for an enclosure matching the Data Center DRAM Tester PCBs.
The enclosure has been optimized mechanically for PCBs in revision 1.2.0.
There are three major parts of the enclosure:

* Bottom tray
* Top lid (installed above the FPGA, connectors and power supply section of the PCB)
* DRAM frame (installed around the DDR4 RDIMM module slot

## Repository structure

The main repository directory contains a LICENSE and README.
The remaining files are stored in the following directories:

* `step` - contains the enclosure parts published as STEP files 
* `img` - contains graphics for this README

## Key Features

* Dust protection
* Improves passive cooling of the FPGA 
* Optimized for desktop usage

## License

[Apache-2.0](LICENSE)