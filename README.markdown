# WireSPI

This is a small library (with a BSD 2-clause license) to act as a SPI slave. The
API is very similar to Arduino's
[Wire](https://www.arduino.cc/en/Reference/Wire) library for I2C, for easy
porting. Communication is half-duplex (even though SPI itself is full-duplex),
as that makes protocols a whole lot easier.

Being similar to the Wire library, it is very easy to port code between the two
libraries.
