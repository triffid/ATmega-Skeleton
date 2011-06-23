ATMega Skeleton: Skeleton libraries for AVR ATmega boards such as the arduino.

Helping out with ATMega Skeleton
--------------------------------

To contribute, get started with the following:

- Fork the project and start hacking.
- Make a pull request.

Setting up a dev environment
----------------------------

You will need avr-gcc toolchain, make and some other packages.
On a Debian clone following will install the build-essentials.

    $ sudo apt-get install make gcc-avr binutils-avr avr-libc

Optionally you can install "avrdude" an AVR controller programming tool:

    $ sudo apt-get install avrdude libusb-dev

The following might help:

- [Detailed help for setting up AVR Dev Environment] [avr_gcc_howto]
- [How to setup and use avrdude] [avrdude_howto]

[avr_gcc_howto]: http://www.nongnu.org/avr-libc/user-manual/install_tools.html
[avrdude_howto]: http://www.ladyada.net/learn/avr/avrdude.html
