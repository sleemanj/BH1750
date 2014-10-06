BH1750
======

An Arduino library for GY-30 (and other) digital light sensor breakout boards containing the BH1750FVI IC.

The board uses I2C for communication. 

2 pins are required to interface to the device.

Datasheet for the light sensor:
http://rohmfs.rohm.com/en/products/databook/datasheet/ic/sensor/light/bh1750fvi-e.pdf


Wiring
------

The GY-30 modules are 5v tolerant, they do the level shifting for you, if you are using a different breakout module please ensure it is tolerant of the voltage you will feed it!

* SCL     ->     SCL (A5, Use Pin 21 on the Arduino Mega)
* SDA     ->     SDA (A4, Use Pin 20 on the Arduino Mega)
* VCC     ->     5v
* GND     ->     GND

Download, Install and Example
-----------------------------

* Download: http://sparks.gogo.co.nz/BH1750.zip
* Open the Arduino IDE (1.0.5)
* Select the menu item Sketch > Import Library > Add Library
* Choose to install the BH1750.zip file you downloaded
* Now you can choose File > Examples > BH1750 > Lux_Meter
