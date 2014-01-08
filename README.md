# GAPfiller GSM900 Version 3 #

Copyright 2014, Close-Haul Communications, Inc.

### Revision History ###

7 January 2014: First commit of OrCAD schematics, PADS PCB layout, Gerber files

### README ###

The GAPfiller GSM900 version 3.0 board is a RF front end daughtercard intended for a single TRX GSM basestation in the 900 MHz band.  
The GAPfiller GSM900 is compatible with the [Ettus Research](https://www.ettus.com/product) USRP software-defined radio systems. 

Modifications to the USRP FPGA and UHD are necessary to run OpenBTS or osmo-bts on the GAPfiller board.  As this work is completed,
these modifications will be added to this repository on github.

As an alternative to the USRP, Close-Haul is developing an adapter board that includes an [Analog Devices AD9963 broadband 
mixed-signal front end](http://www.analog.com/en/analog-to-digital-converters/broadband-codecs/ad9963/products/product.html).  This
board will enable the GAPfiller GSM900 to be used with Xilinx FPGA evaluation boards with FMC interfaces.
 
This design is open source hardware released under the [CERN Open Hardware Licence v1.2](http://www.ohwr.org/licenses/cern-ohl/v1.2).




