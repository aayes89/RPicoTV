# RPicoTV
Using a Raspberry Pi Pico to handle PNG images and output them via VGA.

# Description
It reads image data in PNG format from the set data pin, stores it in a data matrix and generates a VGA signal, sending the image pixels to the TV using that data. The data being sent from the data pin must be in the appropriate format for a PNG image (RGBA8888).

# Applications
As it takes advantage of reading via serial port and/or GPIO pin, it can be linked to another device with WiFi capability which is responsible for receiving the images and sending them to the RPi, so it is possible to say that you have a wireless VGA adapter.

# TODO
* Improve the emulation of the DAC circuit by software.
* Expand the spectrum of image management to JPG and BMP.
* Increase color handling from 256 to 24bits, as well as screen resolution support from 640x480 to 1024x768 or higher.
* Include the possibility of handling HDMI in SD and HD capacity
