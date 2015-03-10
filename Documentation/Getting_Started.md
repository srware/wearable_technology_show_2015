# Intel Hackfest

## Getting Started

At this point you should have the following:

* Intel® Edison & Grove Kit
* Edison USB stick
* PSU
* Micro-USB cable (there is another in your Grove Kit)

You should also have completed the following:

* If using Windows you should have the Edison drivers installed.
* You should have your favourite serial client installed (e.g. Putty)
* You should have your chosen IDE installed so you can begin development (i.e. XDK, Eclipse, Arduino)

> <strong>If you have not completed any of the above please follow the steps outlined [here](Setup.md)</strong>

## Unboxing
Please follow the steps below to assemble and connect your Edison.

* [Assembling Your Edison](https://software.intel.com/en-us/articles/intel-edison-arduino-expansion-board-assembly)
* You can now connect your Grove Base Shield following the instructions below:
	- Remove all power and USB leads from the Edison breakout board before continuing!
	- The Base Shield can be found underneath the LCD screen in your Grove kit (underneath the pink styrofoam).
	- Remove the pink styrofoam from the underside of the Base Shield and locate the pins with the Arduino socket on the Edison breakout board.
	- When you are certain that all pins are aligned correctly, push down evenly on the top of the shield until all pins are firmly located in their socket.
	- Re-attach USB leads and power to the Edison board. You should have a green light on the Base Shield which indicates it is connected correctly and receiving power.
	- Please refer to the 'Grove Start Kit' booklet for further information which can be found underneath the white plastic sensor tray in your Grove kit.
* Connecting your Edison (login details below)
    - [Windows](https://software.intel.com/en-us/articles/getting-started-with-the-intel-edison-board-on-windows#terminal)
    - [Mac](https://software.intel.com/en-us/articles/getting-started-with-the-intel-edison-board-on-mac#terminall)
    - [Linux](https://software.intel.com/en-us/articles/getting-started-with-the-intel-edison-board-on-linux#terminal)

> Edison Login:    <strong>Username:</strong> root  <strong>Password:</strong> hackfest

You should now have your Edison assembled and be able to access the OS through serial.

## WiFi
* [Connect Your Edison To WiFi](https://software.intel.com/en-us/articles/intel-edison-getting-started-wifi) (Make a note of the IP address for future reference)

> <strong>WiFi:</strong> SSID: intel2015 Password: hackfest
> Please ensure your development machine is on the same network!

## Test Your IDE
You are now ready to begin developing. We would recommend starting with a simple example to make sure your IDE is communicating with your Edison correctly.
* [Eclipse (C/C++](https://software.intel.com/en-us/articles/getting-started-with-eclipse-on-intel-iot-platforms#launch)
* [XDK (Javascript)](https://software.intel.com/en-us/articles/getting-started-with-intel-xdk-iot-edition-on-intel-iot-platforms#launch)
* [Arduino](https://software.intel.com/en-us/articles/intel-iot-platforms-blink-led-arduino-ide)
