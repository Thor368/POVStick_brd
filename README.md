POVStick

This is a Persistance Of Vision display in form of a NeoPixel stick. In the future this will be a much shorter and denser handheld LED strip. A SLR will be used in long time exposure mode to "stitch" the image back together as the stick is moved across its field of vision.

The image is stored on a SD card and read by an AVR. The display itself is a string of WS2812 Pixel LEDs. At this (unoptimized) state the AVR is capable of displaying around 75 lines per second at 288 LEDs per line.

Current state: https://youtu.be/oT6iY_f27Is

# Board
The current relase V1.0 is currently in production. The board dimensions are 73x19mm² and feautre:
- ATmega1284 (8kB RAM) @12MHz
- microSD slot
- sleep mode (LED throw-off)
- 4 button inputs
- I²C for small OLED displays
- max. 18V input voltage
