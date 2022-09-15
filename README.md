## Adafruit TCA8418 Keypad Matrix and GPIO Expander Breakout - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/4918"><img src="assets/4918.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TCA8418 Keypad Matrix and GPIO Expander Breakout - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4918

### Description

It's a GPIO expander, it's a keypad matrix driver... its the Adafruit TCA8418 Keypad Matrix and GPIO Expander Breakout - a cute and powerful I2C GPIO expander and keypad matrix driver! This chip is quite fancy, with the ability to act as your I2C multi-tool for handling keypads, buttons or LEDs.

This chip has 18 total 'I/O' pins, 10 columns and 8 rows. You can of course arrange them as a matrix of buttons for a total of 80 switches. Or you can use any subset as individual GPIO input or outputs. The nicest part of the keypad driver is that it has a 10-element event queue, so even if you don't get to the interrupt immediately, keypress and release events will be held for you. Since it's I2C its very easy to use with any microcontroller or computer.

GPIO expanders work like this: you have a board with some number of GPIO but not enough for your project - maybe you need more buttons or LEDs. You could upgrade to a board with massive number of GPIO like the Grand Central, or you could pop on one of these boards. Connect it over I2C and then you can send/receive I2C commands to control the GPIO pins to write and read them. It's going to be slower than direct GPIO access, but maybe that doesn't matter if it takes a millisecond instead of a microsecond. You only need the two I2C pins, and you can even share the I2C port with other sensors and devices. Heck, you can even add more expanders for massive I/O control!

For GPIO expansion, any of the 18 pins can be used as input or output. For inputs, you can also set an optional pull-up and an interrupt output on the INT pin for rising or falling signals. There's also a debouncer that can add a little low-pass filtering for noisy tactile switches. For outputs, you can set them high or low, great for basic LED driving.

For Keypad Matrix driving, theres up to 10 columns and 8 rows. You cannot change a row into a column or vice versa. Pull-ups and matrix scanning is handled for you, with key presses and releases recorded into a 10-element FIFO queue. You can of course set up interrupt output on key press or release so you don't have to poll over and over again. 

We've written both Arduino and CircuitPython/Python libraries for the TCA8418, so you can get started whether you have an Arduino-compatible UNO or a Raspberry Pi 4 - or anything in between. There's also a Linux Kernel driver module if you want to have this natively supported by a single-board-computer.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. There's a built in 3.3V regulator and level shifting on the I2C lines so you can use this with 3V or 5V microcontrollers.

The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the TCA8418 or to chain it with a wide range of other sensors and accessories using a compatible cable. QT Cable is not included, but we have a variety in the shop. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
