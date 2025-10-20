Overview
********

A simple sample that can be used with any Zephyr supported board and
compress & decompress the user data to the console.

Building and Running
********************

The sample can be built and executed on nrf52840dk/nrf52840 as follows::

    west build -b nrf52840dk/nrf52840 zephyr/samples/lorem_ipsum
    west flash

To build for another board, change "nrf52840dk/nrf52840" above to that board's name.
