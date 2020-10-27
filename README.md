# Cmod S7 Hardware Repository

This repository contains Vivado projects for all demos for the Cmod S7.

For more information about the Cmod S7, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [Cmod S7 Out-of-Box Demo](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/demos/oob) | Simple hardware-only demo using the LEDs, RGB LEDs, buttons, and USB-UART bridge. |
| [Cmod S7 Microblaze XADC Demo](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/demos/xadc) | Uses a Microblaze processor to process and print data captured by the XADC analog-to-digital functionality of the Spartan 7 chip. |

## Repository Description

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Cmod S7. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Cmod-S7](https://github.com/Digilent/Cmod-S7) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* https://github.com/Digilent/Cmod-S7-25-OOB
* https://github.com/Digilent/Cmod-S7-25-XADC