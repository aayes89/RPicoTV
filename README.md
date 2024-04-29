# RPicoTV
Using a Raspberry Pi Pico to handle PNG images and output them via VGA.

# Description
It reads image data in PNG format from the set data pin, stores it in a data matrix and generates a VGA signal, sending the image pixels to the TV using that data. The data being sent from the data pin must be in the appropriate format for a PNG image (RGBA8888).
