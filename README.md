# APA102

![APA102](/media/apa102.gif "APA102")

This is an LED project using 240 APA102 LEDs. A dedicated 5V DC power supply is used to power an Arduino Uno as well as
the LEDs.

## Description

As mentioned, this project uses APA102 LEDs. These LED strips have four pins: data, clock, +5 and ground. The LED strip
will need to be powered with an adequate 5v supply (currently using a cheap 5v DC 30amp supply from Amazon). The APA102
data and clock pins are connected to the Arduino Uno's 11 and 13 digital pins, respectively.

The project uses a [Sonoff 4ch WiFi Relay](https://www.itead.cc/sonoff-4ch.html) to switch between different FastLED
presets. This integrates nicely with Google Home, allowing full control via. Google Assistant.