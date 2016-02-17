# AVR-Netino

This project summarizes some patches to the arduino core and bootloader to get the [Pollin AVR-Net-IO board](http://www.pollin.de/AVR-NET-IO‎) programmable by the [arduino IDE](http://www.arduino.cc/en/Main/Software). Additional included are some patched libraries to support the io functions of the AVR-Net-IO board (network, LCD, RFM12, ...)

The philosophy behind the changes is to support many avr's in the core files and to concentrate the board specific details in one file. So porting to other hardware should be very easy. 

## Download

You can download the flashable HEX-File under [releases](https://github.com/cniweb/avr-netino/releases).

## Support us

Comments, suggestions and contributions are welcome!

## CI-Build

Travis Build Status: [![Build Status](https://travis-ci.org/cniweb/avr-netino.svg?branch=master)](https://travis-ci.org/cniweb/avr-netino)

## Maintainers

[@cniweb](https://github.com/cniweb) and [@maassen](https://github.com/maassen)
