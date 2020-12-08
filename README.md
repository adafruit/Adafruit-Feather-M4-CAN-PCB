## Adafruit Feather M4 CAN Express PCB

<a href="http://www.adafruit.com/products/4759"><img src="assets/4759.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Feather M4 CAN Express.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4759

### Description

One of our favorite Feathers, the Feather M4 Express, gets a glow-up here with an upgrade to the SAME51 chipset which has built-in CAN bus support!  Like its SAMD51 cousin, the ATSAME51J19 comes with a 120MHz Cortex M4 with floating point support and 512KB Flash and 192KB RAM. Your code will zig and zag and zoom, and with a bunch of extra peripherals for support, this will for sure be your favorite new chipset for CAN interfacing projects.

At the end of the board we have placed a CAN transceiver chip as well as a 5V converter to generate 5V power to the transceiver even when running on battery. The two CAN signal lines and ground reference signal are available on a 3-pin 3.5mm terminal block. The chip and booster can be put to sleep for power saving. The built in CAN can read or write packets and has support in both Arduino and CircuitPython.

And best of all, it's a Feather - so you know it will work with all our FeatherWings! What a great way to quickly get up and running. It's even pin-compatible with the original Feather M4.

The most exciting part of the Feather M4 CAN is that while you can use it with the Arduino IDE - and it's bonkers fast when you do, you can use it with CircuitPython as well. When you plug it in, it will show up as a very small disk drive with main.py on it. Edit main.py with your favorite text editor to build your project using Python, the most popular programming language. No installs, IDE or compiler needed, so you can use it on any computer, even ChromeBooks or computers you can't install software on. When you're done, unplug the Feather and your code will go with you.

Here are some of the updates you can look forward to when using Feather M4 CAN:

* Measures 2.0" x 0.9" x 0.28" (50.8mm x 22.8mm x 7mm) without headers soldered in
* Light as a (large?) feather - 5 grams
* ATSAME51 32-bit Cortex M4 core running at 120 MHz, 32-bit, 3.3V logic and power
* Hardware CAN bus support with built-in transceiver, 5V booster and terminal connection.
* Floating point support with Cortex M4 DSP instructions
* 512 KB flash, 192 KB RAM
* 2 MB SPI FLASH chip for storing files and CircuitPython code storage.
* No EEPROM
* 32.768 KHz crystal for clock generation & RTC
* 3.3V regulator with 500mA peak current output
* USB Type C connector for USB native support, comes with USB bootloader and serial port debugging
* Built in crypto engines with AES (256 bit), true RNG, Pubkey controller
* Tons of GPIO! 21 x GPIO pins with following capabilities:
  * Dual 1 MSPS 12 bit true analog DAC (A0 and A1) - can be used to play 12-bit stereo audio clips
  * Dual 1 MSPS 12 bit ADC (6 analog pins some on ADC1 and some on ADC2)
  * 6 x hardware SERCOM - Native hardware SPI, I2C and Serial all available
  * 16 x PWM outputs - for servos, LEDs, etc
  * I2S input and output
  * 8-bit Parallel capture controller (for camera/video in)
* Built in 100mA lipoly charger with charging status indicator LED
* Pin #13 red LED for general purpose blinking
* Power/enable pin
* 4 mounting holes
* Reset button

The Feather M4 Can Express also comes with a Mini NeoPixel and 2 MB SPI Flash storage. You can use the SPI Flash storage like a very tiny hard drive. When used in CircuitPython, the 2 MB flash acts as storage for all your scripts, libraries and files. When used in Arduino, you can read/write files to it, like a little datalogger or SD card, and then with our helper program, access the files over USB.

Easy reprogramming: the Feather M4 CAN comes pre-loaded with the UF2 bootloader, which looks like a USB storage key. Simply drag firmware on to program, no special tools or drivers needed! It can be used to load up CircuitPython or Arduino IDE (it is bossa-compatible)

Comes fully assembled and tested, with the UF2 USB bootloader. We also toss in some headers so you can solder it in and plug into a solderless breadboard.

Lipoly battery and USB cable not included (but we do have lots of options in the shop if you'd like!)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
