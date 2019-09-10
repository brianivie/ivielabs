# Introduction to Arduino

## Install the Arduino IDE and the CH340 USB Driver
IDE stands for “Integrated Development Environment.”  It typically refers to a single program that connects to the compiler, linker, and other needed utility programs in the background to compile, link and run programs.  The Arduino IDE is written in Java, it is free (though they do ask for a donation), and it runs on Windows, Mac, and Linux operating systems.

Currently the latest version of the desktop IDE for Arduino is version 1.8.5.  You can find it on the web page here: https://www.arduino.cc/en/Main/Software  There is a new version of the Arduino IDE that runs inside a browser.  This one costs a subscription fee at the moment, so we’re going to go with the free desktop version instead.

The Arduino IDE sets up a standard USB driver.  This works for the USB chip on the official Arduino board.  We will be using a “clone” of that board that uses a different USB chip (because it was cheaper).  You will need to separately install the USB Drivers for the CH340 USB Chip. 

The CH340 USB Drivers can be found here:  https://sparks.gogo.co.nz/ch340.html
and (for the Latest MacOS) here: https://github.com/adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver/blob/master/CH34x_Install_V1.4.pkg

It is probably a good idea not to plug the Arduino into your computer until after you have installed the driver for it, otherwise the operating system will go looking for the driver on its own, and it has been my experience it doesn’t do a very good job finding one.  Once the driver is installed, plug in the USB cable to the Arduino and the computer should recognize it and use the correct driver.

You will have completed this first step if you can upload and run the “Blink” program to your Arduino.  To do this first run the Arduino IDE:


