# IHP__COMM-3889
Nano SPI device IP

Single-technology IP library.

- doc/     : user documentation
- dependencies/ : sub-cells and blocks
- release/v.1.0.0 : immutable versioned deliveries

## Overview and Origin


The Nano SPI Device is a lightweight SPI slave peripheral designed to provide a simple interface for controlling output signals and accessing an internal 8-bit storage register. The device receives commands through an SPI interface and provides the corresponding response through the SPI MISO line.

The device was developed as a digital IP targeting the IHP 130~nm CMOS technology. The implementation was performed using the IHP 130nm PDK.

This IP is derived form the Apache-2.0-licensed https://tinytapeout.com/chips/ttihp25a/tt_um_zedulo_spitest1. It provides an implementation of this peripheral communication interface in IHP 130nm PDK, performed using OpenLane Flow provided by Tiny Tapeout. 

The configuration set by its author was ported to a regular LibreLane Flow in order to reproduce with the highest fidelity as possible the original output of the original Flow. 

The current release targets the IHP130nm CMOS PDK. In addition to the synthesizable RTL implementation, the release includes a placed-and-routed hard macro and the associated logical, physical, timing, and verification views required for integration into a larger design.