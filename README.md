# SEC Xtractor (Hardware)
A tool for directly dumping memory chips and identifying on-chip debugging/programming interfaces. Can act as UART-to-USB converter and JTAG adapter. 

## NAND Adapter
This adapter converts the GPIO pins of the SEC Xtractor to the JEDEC standardized NAND pin configuration.

## NOR Adapter
This adapter converts the GPIO pins of the SEC Xtractor to the JEDEC standardized NOR pin configuration.

# Documentation
A short documentation for the usage of the SEC Xtractor can be found in the folder *documentation*.
The firmware that is used for the device can be found in the [firmware repository][3].

# Socket Adapters
The following TSOP-48 socket adapters can be used for the NAND and NOR adapter PCBs:
* SXA-TSOP48 SA 247
* SXA-TSOP48 SB 247

For the main ZIF socket, all DIL adapters with 48 or less pins can be used.

# Authors
SEC Xtractor Revision 1.0:
* Thomas Weber of [SEC Consult][1]

SEC Xtractor Revision 1.21:
* Thomas Weber of [SEC Consult][1]

SEC Xtractor Revision 1.31:
* Thomas Weber of [SEC Consult][1]

NAND adapter revision 1.0:
* Thomas Weber of [SEC Consult][1]

NOR adapter revision 1.0:
* Thomas Weber of [SEC Consult][1]

NOR adapter revision 1.1:
* Thomas Weber of [SEC Consult][1]

## License
The SEC Xtractor design and documentation is distributed under a [Creative Commons 4.0][2] license. This means that you can share and adapt the work, but you must attribute the work to the original author.

[1]: https://www.sec-consult.com
[2]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[3]: https://github.com/sec-consult/SEC-Xtractor_Firmware
