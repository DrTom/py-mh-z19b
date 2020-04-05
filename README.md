MH-Z19B CO2-Sensor Asynchronous Device Library for Python
=========================================================

This library supports reading of CO2 values from a MH-Z19B via UART.
The MH-Z19B is an affordable nondispersive infrared CO2 sensor from
Zhengzhou Winsen Electronics Technology Co., Ltd.

The coded has been successfully tested with

* MicroPython 1.11 on a ESP32 Wrover DevBoard
* Python 3.7 on MacOS with a USB-UART adapter

Dependencies
------------

* MicroPython (1.11 tested) or Python (3.7 tested)
* logging, see [micropython-logging] for MicroPython
* asyncio, or [uasyncio] for MicroPython

Usage
-----

See the provided `example.py` file.


Limitations and Restrictions
----------------------------

* Only the CO2 read command is implemented.


[micropython-logging]: https://pypi.org/project/micropython-logging/
[uasyncio]: https://pypi.org/project/micropython-uasyncio/
