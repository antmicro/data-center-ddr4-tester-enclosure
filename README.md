# Data Center DDR4 Tester Enclosure

Copyright (c) 2022-2023 [Antmicro](https://antmicro.com)

![Data Center DDR4 Tester Enclosure](img/ddr4-tester-enclosure.png)

## Overview

This repository contains open hardware mechanical design files for an enclosure matching the [Data Center DRAM Tester](https://github.com/antmicro/data-center-dram-tester) PCBs.
The enclosure has been optimized mechanically for PCBs in revision 1.2.0.
There are three major parts of the enclosure:

* base - supporting the DRAM tester PCB from the bottom,
* front lid - installed above the FPGA, connectors and power supply section of the PCB,
* back lid - installed around the DDR4 RDIMM module slot.

Additionally there are two mechanical components exposing the LEDs installed on the DRAM tester PCB:

* PMMA lightpipe - custom lightpipe laser-cut from acrylic glass (PMMA),
* lightpipe separator - groups LED lightpipes and keeps the custom PMMA lightpipes from stray light.

## Repository structure

The main repository directory contains a LICENSE and a README.
The remaining files are stored in the following directories:

* `step` - contains the enclosure parts published as STEP files 
* `stl` - contains the enclosure parts for 3D printing in STL format
* `dxf` - contains the production file for PMMA laser cutting
* `img` - contains graphics for this README

## Key features

* Dust protection
* Improves passive cooling of the FPGA 
* Optimized for desktop usage

## License

[Apache-2.0](LICENSE)
